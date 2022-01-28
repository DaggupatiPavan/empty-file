pipeline{
  agent any
  stages{
    stage('Git Clone'){
          steps{
            git 'https://github.com/DaggupatiPavan/empty-file.git'
          }
    }
    stage('Validate'){
          steps{
            sh 'mvn validate'
          }
    }
    stage('compile'){
          steps{
            sh 'mvn compile'
          }
   }
}
    

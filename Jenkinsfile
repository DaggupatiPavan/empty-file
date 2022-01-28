pipeline{
    agent any
    stages{
        stage('Git Clone'){
            steps{
                git 'https://github.com/DaggupatiPavan/empty-file.git'
            }
        }
        stage('Test'){
            steps{
                echo "Test sucessful"
            }
        }
        stage('Build'){
            steps{
                echo "Build Sucessful"
            }
        }
    }
}

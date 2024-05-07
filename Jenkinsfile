pipeline {
    agent any

    stages{
        stages('build'){
            steps{
                sh 'npm install'
            }
        }

        stage('test'){
            steps{
                sh 'echo"testing the application"'
            }
        }
        stage('deploy'){
            steps{
                sh 'echo"deploying the application"'
            }
        }
    }
}
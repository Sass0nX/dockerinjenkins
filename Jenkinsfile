pipeline{
    agent any
    stages{
        stage('python'){
            agent {
                docker {image 'python:latest'}
                steps{
                    sh 'python app.py'
                }
            }
        }
        stage('python'){
            steps{
                sh 'node --version'

            }
        }    
    }
}
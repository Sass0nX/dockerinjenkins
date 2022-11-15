pipeline{
    agent any
    stages{
        stage('nodejs'){
            agent {
                docker {image 'node:16.13.1-alpine'}
                steps{
                    sh 'node --version'
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
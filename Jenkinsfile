pipeline{
    agent any
    stages{
        stage('python'){
            agent {
                docker {image 'sassisam/maorpython'}
            }
            steps{
                sh 'python app.py'
                }          
        }
        stage('node'){
            agent{
                docker {image 'node:16.13.1-alpine'}
            }
            step {
                sh 'node --version'
                }

        }    
    }
}
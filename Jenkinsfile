pipeline{
    agent any
    stages {
        stage('Clean'){
            steps {
               sh 'echo Clonning....'
            }
        }
         stage('Check'){
            steps {
               sh 'echo Building....'
            }
        }
        stage('Test'){
            steps {
               sh 'echo Testing....'
            }

        }
        stage('Build'){
            steps {
                sh 'echo Building'
            }
        }
        stage('Tag Release'){
            steps {
               sh 'echo Tagging....'
            }
        }
        stage('Publish Artifact to Nexus'){
            steps {
               sh 'echo Publishing....'
            }

        }
        stage('Docker Image'){
            steps {
               sh 'echo Building....'
            }

        } 
        stage('Push Docker Image to Nexus'){
            steps {
               sh 'echo Pushing Image....'
            }

        }
        stage('Deploy to DEV'){
            steps {
               sh 'echo Deploying....'
            }
        }
        stage('Deploy to TRIAL'){
            steps {
               sh 'echo TRIAL....'
            }
        }
        stage('Deploy to STAGE'){
            steps {
               sh 'echo STAGE....'
            }
        }
        stage('UAT Testing'){
            steps {
               sh 'echo UAT Testing....'
            }
        }

        stage('Deploy to PROD'){
            steps {
               sh 'echo PROD....'
            }
        }
        stage('User Acceptance Test'){
            steps {
               sh 'echo Testing....'
            }
        }

    } 

}
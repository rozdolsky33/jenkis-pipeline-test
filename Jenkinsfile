pipeline{
    agent any
    stages {
        stage('Cloning'){
            steps {
               sh 'echo Clonning....'
            }
        }
         stage('Build'){
            steps {
               sh 'echo Building....'
            }
        }
        stage('Test'){
            steps {
               sh echo 'Testing....'
            }

        }
        stage('Tag release'){
            steps {
               sh 'echo Tagging....'
            }

        }
        stage('Publish Artifact'){
            steps {
               sh 'echo Publishing....'
            }

        }
        stage('Image Build'){
            steps {
               sh 'echo Building....'
            }

        } 
        stage('Image Push'){
            steps {
               sh 'echo Pushing Image....'
            }

        }
        stage('Deploy to DEV'){
            steps {
               sh 'echo Deploying....'
            }
        }

    } 

}
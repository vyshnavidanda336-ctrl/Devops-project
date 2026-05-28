pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code pulled from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Docker image'
            }
        }

        stage('Push') {
            steps {
                echo 'Pushing Docker image'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to Kubernetes'
            }
        }

    }
}
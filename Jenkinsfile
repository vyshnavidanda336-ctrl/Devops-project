pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t vyshnavidanda336/devops-app:v5 .'
            }
        }

        stage('Push Docker Image') {
            steps {
                sh 'docker push vyshnavidanda336/devops-app:v5'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Next: deploy v5 image to Kubernetes'
            }
        }
    }
}
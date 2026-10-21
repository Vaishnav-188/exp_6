pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code fetched from GitHub'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Application test passed'
            }
        }
        stage('Docker Build') {
            steps {
                echo 'Docker build stage'
            }
        }
        stage('Kubernetes Deploy') {
            steps {
                echo 'Kubernetes deployment stage'
            }
        }
        stage('Verify Deployment') {
            steps {
                echo 'Deployment verification stage'
            }
        }
    }
}

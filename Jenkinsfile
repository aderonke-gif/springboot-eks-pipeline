pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Spring Boot app...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to EKS...'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...'
            }
        }
        stage('Build') {
            steps {
                echo 'Simulating build step...'
                sh 'echo Building project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
                sh 'echo All tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment stage (placeholder)...'
            }
        }
    }
    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}

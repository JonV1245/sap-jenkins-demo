pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning GitHub repo...'
            }
        }
        stage('Simple Shell Task') {
            steps {
                sh 'echo Hello from Jenkins Pipeline!'
            }
        }
    }
}

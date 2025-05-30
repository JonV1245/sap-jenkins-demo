pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning GitHub repo...'
            }
        }
        stage('Run Script') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}

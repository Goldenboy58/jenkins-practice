pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'python3 --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'python3 app.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}

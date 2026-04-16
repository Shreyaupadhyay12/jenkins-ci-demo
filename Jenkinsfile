pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                bat 'python test_app.py'
            }
        }
    }
}
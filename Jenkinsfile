pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the GitHub repository
                git  'https://github.com/efratlt/test.git'
            }
        }
        stage('Test') {
            steps {
                // Run pytest to execute tests
                sh 'python -m unittest TestAddFunction.py'
            }
        }
    }
}
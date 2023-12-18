pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                // Run pytest to execute tests
                sh 'python -m unittest TestAddFunction.py'
            }
        }
    }
}
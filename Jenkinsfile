pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Welcome to Jenkins World'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
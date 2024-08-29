pipeline {
    agent any

    stages {
        stage('Logging..') {
            steps {
                bat 'echo Rana'
            }
        }
        stage('Build') {
            steps {
                bat 'make all'
            }
        }
        stage('Test') {
            steps {
                bat 'make test'
            }
        }
    }
}

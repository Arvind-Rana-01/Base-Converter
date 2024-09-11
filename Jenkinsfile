pipeline {
    agent any

    stages {
        stage('Logging..') {
            steps {
                bat 'echo Rana'
                bat 'gcc --version'
                bat 'make --version'
            }
        }
        stage('Build') {
            steps {
                bat 'make'
            }
        }
        stage('Test') {
            steps {
                bat 'make test'
            }
        }
    }
}

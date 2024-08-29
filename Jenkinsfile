pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'make all'
            }
        }
        stage('Test') {
            steps {
                sh 'make test'
            }
        }
        stage('Deploy') {
            when {
                branch 'main'
            }
            steps {
                sh 'make deploy'
            }
        }
    }
}

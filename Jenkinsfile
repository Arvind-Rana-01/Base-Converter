pipeline {
    agent any
	
    stages {
        stage('Check GCC Version') {
            steps {
                bat 'gcc --version'
            }
        }
        stage('Build') {
            steps {
                bat 'gcc Base-Converter.c -o Base-Converter'
            }
        }
	
    }
}

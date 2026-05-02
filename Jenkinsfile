pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                bat 'javac test.java'
            }
        }
        stage('run') {
            steps {
                bat 'java test'
            }
        }
    }
}
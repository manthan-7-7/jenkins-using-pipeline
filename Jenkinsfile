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


     post{
        always{
            bat'echo "always"'
        }
    
        success{
            bat'echo "build success"'
        }
        failure{
            bat'echo "build failure"'
        }
    }
}
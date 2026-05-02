pipeline{

    agent any

    stages{

        stage("compile"){
            steps{
             sh 'javac test.java'
            }
        }

        stage("runn"){
            steps{
               sh "java test"
            }
        }
    }
}
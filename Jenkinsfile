pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('checkout') {
            steps {
                deleteDir()
                checkout scm
         }
    }
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('Deploy') {
            steps {
               sh 'echo deploying to test'
            }
        }
    }
    
}
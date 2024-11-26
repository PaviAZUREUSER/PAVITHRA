pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                sh 'npm install'
            }
        }
        stage('build') {
            steps {
                sh 'echo "create application..."'
            }
        }
        stage('test') {
            steps {
                sh 'echo " testing application..."'
            }
        }
        stage('Deploy nodejs application') {
            steps {
                echo "Deploying application"
            }
        }
    }
} 

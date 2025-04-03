pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // For example: sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // For example: sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // For example: use SSH to copy files or run deployment scripts
            }
        }
    }
}




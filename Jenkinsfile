pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'ls'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'cat app.txt'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Building Docker image...'
                sh 'docker build -t ci-demo:latest .'
            }
        }
    }
}  

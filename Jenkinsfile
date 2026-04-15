pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/maheshpatimini/mahesh.git'
            }
        }
        stage('Build') {
            steps { echo 'Executing Build Stage...' }
        }
        stage('Test') {
            steps { echo 'Executing Test Stage...' }
        }
        stage('Deploy') {
            steps { echo 'Deploying to EC2 Instance...' }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -la'
                sh 'node --version'
                sh 'npm --version'
                sh 'npm install'
                sh 'npm run build'
                sh 'ls -la'
            }
        }
    }
}
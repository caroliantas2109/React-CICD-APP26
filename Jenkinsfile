pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'dir'
                bat 'node --version'
                bat 'npm --version'
                bat 'npm install'
                bat 'npm run build'
                bat 'dir'
            }
        }
    }
}
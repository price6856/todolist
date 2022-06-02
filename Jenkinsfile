pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'This is a test'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run start'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is a deploy'
            }
        }
    }
}
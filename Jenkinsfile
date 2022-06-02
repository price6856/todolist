pipeline {
    agent any
    environment {
        CI = 'false'
    }
    stages {
        stage('Test') {
            steps {
                echo 'This is a test'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is a deploy'
            }
        }
    }
}
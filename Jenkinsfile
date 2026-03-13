pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Pipeline Triggered by GitHub Webhook"
            }
        }

        stage('Test') {
            steps {
                sh 'echo Testing Pipeline'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deployment Stage'
            }
        }
    }
}

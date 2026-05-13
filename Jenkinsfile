pipeline {

    agent any

    stages {

        stage('Clone Check') {
            steps {
                echo 'GitHub repository cloned successfully'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Pipeline running successfully'
            }
        }
    }
}
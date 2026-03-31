pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building app version 2'
            }
        }

        stage('Test') {
            steps {
                echo 'Running improved test suite'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying version 2'
            }
        }
    }

    post {
        success {
            echo 'Deployment done successfully'
        }
    }
}

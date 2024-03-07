pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add commands to build your project
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add commands to run tests
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add commands to deploy your application
            }
        }
    }

    post {
        always {
            catchError {
                echo 'Pipeline succeeded!'
            }
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}


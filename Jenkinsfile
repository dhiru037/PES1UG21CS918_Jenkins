pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Compile the .cpp file using a shell script
                    echo 'Build'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    // Print the output of the compiled .cpp file
                    echo ' test'
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Your deployment steps go here
                    echo 'Deploying...'
                    // Add your deployment commands or scripts
                }
            }
        }
    }

    post {
        failure {
            echo 'Pipeline failed!'
        }
    }
}

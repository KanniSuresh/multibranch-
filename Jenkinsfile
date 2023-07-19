pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Shell script to perform the build step
                sh 'echo "Building.."'
                // Add additional build commands as needed
            }
        }
        stage('Deploy') {
            steps {
                // Placeholder for deployment step
                echo 'Deployment step will go here'
                // Add actual deployment commands as needed
            }
        }
    }

    post {
        success {
            // Actions to be performed if the pipeline is successful
            echo 'Pipeline executed main brach!'
        }
        failure {
            // Actions to be performed if the pipeline fails
            echo 'Pipeline failed!'
        }
    }
}

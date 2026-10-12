pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building login feature: ${env.BRANCH_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo "Testing branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying branch: ${env.BRANCH_NAME}"
            }
        }
    }
}
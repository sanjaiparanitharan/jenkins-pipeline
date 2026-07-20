pipeline {

    agent any

    stages {

        stage('Checkout') {

            steps {

                echo "Checking out source code..."

                checkout scm
            }
        }

        stage('Build') {

            steps {

                echo "Building application..."

                echo "Build completed successfully."
            }
        }

        stage('Test') {

            steps {

                echo "Running test cases..."

                echo "All test cases passed."
            }
        }

        stage('Deploy') {

            steps {

                echo "Deploying application..."

                echo "Application deployed successfully."
            }
        }

    }

    post {

        always {

            echo "Pipeline Finished."
        }

        success {

            echo "Pipeline Executed Successfully."
        }

        failure {

            echo "Pipeline Failed."
        }

    }

}

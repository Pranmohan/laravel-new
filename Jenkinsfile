pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from your version control system
                sh "echo 'this stage is checking out the code'"
            }
        }

        stage('Install dependencies') {
            steps {
                // Install Node.js dependencies using npm or yarn
                sh "echo 'this stage is installing the dependency'"
            }
        }

        stage('Build') {
            steps {
                // Build your Node.js application (if necessary)
                sh "echo 'this stage is for building the code'"
            }
        }

        stage('Deploy') {
            steps {
                // SSH into the deployment server and deploy the application
          
                    sh "echo 'deployment successfully'"
                }
            }
        }
    }

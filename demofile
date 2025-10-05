pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code from version control
                //git 'https://githddub.com/your/repository.git'
		echo 'checkout stage'
            }
        }
        stage('Build') {
            steps {
                // Use Maven to build your project
                echo 'build stage'
            }
        }
        stage('Test') {
            steps {
                // Run tests if applicable
                echo 'test stage'
            }
        }
    }
    

    post {
        success {
            // This block will be executed if the pipeline runs successfully
            echo 'Pipeline executed successfully!'
        }
        failure {
            // This block will be executed if the pipeline fails
            echo 'Pipeline failed!'
        }
    }
}

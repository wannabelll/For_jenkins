pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {  // New stage named 'Build'
            steps {
                echo 'Running Build'
                // Add your build steps here
            }
        }
        stage('Test') {   // Another new stage named 'Test'
            steps {
                echo 'Running Tests'
                // Add your test steps here
            }
        }
    }
}

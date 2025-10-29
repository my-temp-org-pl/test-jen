pipeline {
    agent any // Specifies that the pipeline can run on any available agent

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...' // Prints a message to the console
                // Add your build commands here, e.g., sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...' // Prints a message to the console
                // Add your test commands here, e.g., sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application from git ..' // Prints a message to the console
                // Add your deployment commands here, e.g., sh 'scp target/app.jar user@server:/path/to/deploy'
            }
        }
    }
}

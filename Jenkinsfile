pipeline {
    agent any

 parameters {
        string(name: 'USERNAME_TO_ADD', defaultValue: '', description: 'Enter the username to add to text file')
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the repository
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Add build steps here
                echo 'Building the project'
            }
        }
    }
}

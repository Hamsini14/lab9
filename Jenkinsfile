pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // This is where you'd run 'mvn install' or 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
                // This is where you'd run 'pytest' or 'junit'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to staging environment...'
                // This is where you'd run a shell script to move files
            }
        }
    }
}

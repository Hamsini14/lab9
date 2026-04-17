pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the Java program...'
                bat 'javac BinarySearch.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Running the Java program...'
                bat 'java BinarySearch'
            }
        }
    }
}

pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the Java program...'
                sh 'javac BinarySearch.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Running the Java program...'
                sh 'java BinarySearch'
            }
        }
    }
}
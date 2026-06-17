pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Jenkins automatically clones repo here
                checkout scm
            }
        }

        stage('Show Files') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Read README') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}

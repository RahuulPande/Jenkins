pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn cleen install' // typo: 'cleen' instead of 'clean'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}

pipeline {
    agent {
        label 'windows && a102'
    }
    stages {
        stage('Test') {
            steps {
                bat 'pytest'
            }
        }
    }
}
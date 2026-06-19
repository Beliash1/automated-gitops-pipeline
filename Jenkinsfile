pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t my-gitops-app:latest .'
            }
        }
    }
}

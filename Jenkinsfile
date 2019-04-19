pipeline {
    agent { docker { image 'node:10-jessie' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
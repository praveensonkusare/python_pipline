pipeline {
    agent { docker { image 'python:3.9.7' } }
    stages {
        stage('build') {
            steps {
                sh 'sum.py'
            }
        }
    }
}

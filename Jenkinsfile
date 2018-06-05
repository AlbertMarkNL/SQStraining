pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('dev') {
            steps {
                echo 'dev stage'
            }
            stage('build') {
            steps {
                sh 'python --version'
            }
        stage('build') {
            steps {
                echo 'build stage'
                sh 'python --version'
            }
        }
    }
}

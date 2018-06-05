pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('dev') {
            steps {
                echo 'dev stage'
            }
        }
        stage('test') {
            steps {
               echo 'test stage'
            }
        }
        stage('build') {
            steps {
                echo 'build stage'
                sh 'python --version'
            }
        }
    }
}

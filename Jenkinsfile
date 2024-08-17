/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.12.5-alpine3.20' } }
    /*
    environment {
        PATH = "/Users/avilior/.pyenv/shims/python;$PATH"
    }
    */
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

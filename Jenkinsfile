/* Requires the Docker Pipeline plugin this is a comment again test */
pipeline {
    agent { docker { image 'golang:1.27.2-alpine3.24' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
                echo 'Building the application...'
            }
        }
    }
}


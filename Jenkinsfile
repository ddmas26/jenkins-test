Jenkinsfile (Declarative Pipeline)

/* Requires the Docker Pipeline plugin this is a comment */
pipeline {
    agent { docker { image 'golang:1.27.2-alpine3.24' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}


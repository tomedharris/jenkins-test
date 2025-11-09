pipeline {
    agent { docker { image 'golang:1.25.3-alpine3.22' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}

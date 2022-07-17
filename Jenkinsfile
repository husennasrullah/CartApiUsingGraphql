pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                sh 'go build'
            }
        }
        stage('Test') {
            steps {
                sh 'go test ./unittest'
            }
        }
    }
}

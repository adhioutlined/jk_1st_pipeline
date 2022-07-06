pipeline {
    agent { docker { image 'whalesay:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'cowsay boo'
            }
        }
    }
}

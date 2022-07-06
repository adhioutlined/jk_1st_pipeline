pipeline {
    agent { docker { image 'docker/whalesay' } }
    stages {
        stage('build') {
            steps {
                sh 'cowsay boo'
            }
        }
    }
}

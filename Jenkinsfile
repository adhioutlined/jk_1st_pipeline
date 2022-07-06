pipeline {
    agent { docker { image 'whalesay' } }
    stages {
        stage('build') {
            steps {
                sh 'cowsay boo'
            }
        }
    }
}

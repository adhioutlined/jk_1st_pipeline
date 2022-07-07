pipeline {
    agent { docker { image 'docker/whalesay' } }
    stages {
        stage('build') {
            steps {
                sh 'cowsay "Hi, Hello... I'am gr00t"'
            }
        }
    }
}

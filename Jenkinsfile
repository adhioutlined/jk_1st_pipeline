pipeline {
    agent { docker { image 'docker/whalesay' } }
    stages {
        stage('build') {
            steps {
                sh 'tgl=($date)'
                sh 'cowsay "Hi, Hello... Today is $tgl"'
            }
        }
    }
}

pipeline {
    agent { docker { image 'docker/whalesay' } }
    stages {
        stage('build') {
            steps {
                sh 'cowsay I_am_gr00t'
            }
        }
    }
}

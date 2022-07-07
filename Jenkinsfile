pipeline {
    agent { docker { image 'docker/whalesay' } }
    stages {
        stage('build') {
            steps {
                sh 'cowsay "Hi, Hello... Iam gr00t"'
            }
        }
    }
}

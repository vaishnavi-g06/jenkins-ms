pipeline {
    agent {
        label 'linux'
    }

    stages {
        stage('Build') {
            steps {
                sh 'docker build -t my-image .'
            }
        }
    }
}

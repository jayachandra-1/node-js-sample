pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                sh 'git credentialsId: 'jaya', url: 'git@github.com:jayachandra-1/node-js-sample.git''
            }
        }
    }
}

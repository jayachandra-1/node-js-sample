pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                sh 'git credentialsId: 'jaya', url: 'https://github.com/Jayachandra-2/node-js-sample.git''
            }
        }
    }
}

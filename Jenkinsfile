pipeline {
    agent {
        docker {
            image 'node:12.18-alpine'
            args '-p 9229:9229'
        }
    }
    stages {
        stage('Build'){
            steps {
                sh 'npm install'
            }
        }

    }
}

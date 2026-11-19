pipeline {
    agent {
        docker {
            image 'node:16'
        }
    }
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install --save'
            }
        }
    }
}

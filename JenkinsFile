pipeline {
    agent {
        docker {
            image 'ubuntu'
        }
    }
    stages {
        stage('Build Docker image') {
            steps {
                sh 'docker build -t todolistapp .'
            }
        }
    }
}

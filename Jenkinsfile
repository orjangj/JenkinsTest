pipeline {
    agent {
        docker { image 'python:2.7.15' }
    }
    stages {
        stage('Test') {
            steps {
		sh 'pip --version'
                sh 'python --version'
            }
        }
    }
}

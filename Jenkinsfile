pipeline {
    agent {
        docker { image 'python:2.7.15' }
    }
    stages {
        stage('Test') {
            steps {
                sh './run_hello'
            }
        }
    }
    post {
        always {
            junit 'build/reports/**/*.xml'
        }
    }
}

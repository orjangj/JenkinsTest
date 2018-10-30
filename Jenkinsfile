pipeline {
  agent { docker 'python:2.7.15' }
  stages {
    stage('build') {
      steps {
        sh 'pip --version'
        sh 'python --version'
      }
    }
  }
}
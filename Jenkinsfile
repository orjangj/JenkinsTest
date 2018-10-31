pipeline {
  stages {
    stage('Example') {
      agent {docker 'python:2.7'}
      steps {
        python --version
      }
    }
  }
}
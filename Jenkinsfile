pipeline {
  agent {docker 'python:2.7'}
  stages {
    stage('Example') {
      steps {
        sh './run_hello.sh'
      }
    }
  }
}
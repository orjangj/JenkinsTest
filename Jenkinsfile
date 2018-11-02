pipeline {
  agent {docker 'python:2.7'}
  stages {
    stage('Test1') {
      steps {
        sh 'python hello.py'
      }
    }
    stage('Test2') {
        sh 'bash ./run_hello.sh'
    }
    stage('Test3') {
        sh './run_hello.sh'
    }
  }
}
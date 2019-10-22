pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            sh '''



pwd; ls'''
          }
        }
        stage('') {
          steps {
            sh 'ls -lhtr && pwd'
          }
        }
      }
    }
  }
}
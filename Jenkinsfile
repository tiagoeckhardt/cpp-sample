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
        stage('Prod') {
          steps {
            sh 'ls -lhtr && pwd'
          }
        }
      }
    }
    stage('Constru��o') {
      steps {
        sh 'ls && pwd'
      }
    }
  }
}
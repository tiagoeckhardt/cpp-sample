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
    stage('Construção') {
      steps {
        sh 'ls && pwd'
      }
    }
    stage('Gerar') {
      steps {
        sh 'ls; pwd'
      }
    }
  }
}
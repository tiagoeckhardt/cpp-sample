pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''



pwd; ls'''
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
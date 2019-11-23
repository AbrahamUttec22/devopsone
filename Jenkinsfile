pipeline {
  agent any
  stages {
    stage('Instanciando') {
      steps {
        sh 'uname -a'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'php --version'
          }
        }

        stage('Build Web') {
          steps {
            sh 'php --version'
          }
        }

      }
    }

  }
}
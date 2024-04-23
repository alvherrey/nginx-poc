pipeline {
  agent any
  stages {
    stage('Test step') {
      agent {
        docker {
          image 'nginx:latest'
        }

      }
      steps {
        sh 'echo hola'
      }
    }

  }
}
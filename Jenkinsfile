pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
        echo "Do something"
        hostname
        pwd
        ls
        '''
      }
    }
    stage('Test') {
      steps {
        echo "Pruebas"
      }
    }
    stage('Deploy') {
      steps {
        echo "Terminado"
      }
    }
  }
}

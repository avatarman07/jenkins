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
        echo "test1"
        '''
      }
    }
    stage('Test') {
      steps {
        sh '''
        echo "Pruebas"
        ls
        echo "webhook"
        '''
      }
    }
    stage('Deploy') {
      steps {
        echo "Terminado"
      }
    }
  }
}

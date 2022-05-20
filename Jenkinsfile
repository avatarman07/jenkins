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
        touch "abre.txt"
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

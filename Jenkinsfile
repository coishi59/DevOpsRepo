pipeline {
  agent any
  stages {
    stage('Instanciando') {
      steps {
        echo 'Iniciando proceso'
        bat 'systeminfo'
      }
    }

    stage('build') {
      steps {
        bat 'gcc --version'
        bat 'php --version'
      }
    }

  }
}
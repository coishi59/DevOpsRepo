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
      parallel {
        stage('build') {
          steps {
            bat 'gcc --version'
          }
        }

        stage('build web') {
          steps {
            bat 'php --version'
          }
        }

      }
    }

  }
}
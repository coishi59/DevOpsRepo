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

        stage('') {
          steps {
            bat 'php --version'
          }
        }

      }
    }

  }
}
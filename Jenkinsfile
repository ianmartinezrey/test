pipeline {
  agent any
  stages {
    stage('approval') {
      steps {
        input 'Por favor aprueba '
      }
    }

    stage('test') {
      steps {
        echo 'Se ejecutaron las pruebas'
      }
    }

    stage('deploy') {
      steps {
        echo 'Creación del artefacto'
      }
    }

  }
}
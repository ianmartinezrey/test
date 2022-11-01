pipeline {
  agent any
  stages {
    stage('code') {
      steps {
        error 'Hay un error en el codigo'
      }
    }

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
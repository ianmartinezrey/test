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
        input(message: 'Por favor aprueba ', id: '1', ok: '2')
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
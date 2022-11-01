pipeline {
  agent any
  stages {
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

    stage('approval') {
      steps {
        input(message: 'Por favor aprobar', id: '1', ok: '2')
      }
    }

  }
}
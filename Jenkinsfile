pipeline {
  agent any
  stages {
    stage('TxWeb') {
      parallel {
        stage('TxWeb') {
          steps {
            build 'Tx_Web'
          }
        }

        stage('TxAPI') {
          steps {
            build 'Tx_API'
          }
        }

      }
    }

  }
}
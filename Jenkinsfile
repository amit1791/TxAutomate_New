pipeline {
  agent any
  stages {
    stage('Tx_Web') {
      parallel {
        stage('Tx_Web') {
          steps {
            sh '''c:
cd D:\\Workspace\\ocucumber-jvm-template-master-Orignal 2.0
mvn test -Dcucumber.options="--tags @Amazon"
'''
          }
        }

        stage('Tx_API') {
          steps {
            sh '''c:
cd D:\\Workspace\\ocucumber-jvm-template-master-Orignal 2.0
mvn test -Dcucumber.options="--tags @APItests"
'''
          }
        }

      }
    }

  }
}
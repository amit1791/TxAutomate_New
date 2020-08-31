pipeline {
  agent any
  stages {
    stage('TxWeb') {
      steps {
        sh '''d:
cd D:\\TestingXperts\\cucumber-jvm-template-master-2.0_New_Updated
mvn test -Dcucumber.options="--tags @Amazon"'''
      }
    }

  }
}
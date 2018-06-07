pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello Jenkins'
        sh 'java -version'
      }
    }
  }
}
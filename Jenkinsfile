pipeline {
  agent {
    label 'jdk8'
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
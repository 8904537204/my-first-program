pipeline {
  agent any
  stages {
    stege {'Hello'} {
      steps {
        sh 'mvn --version'
        sh 'mvn clean install'
      }
    }
  }
}

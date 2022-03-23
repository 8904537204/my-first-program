pipeline {
  agent any
  stages {
    stege {'log version info'} {
      steps {
        sh 'mvn --version'
        sh 'mvn clean install'
      }
    }
  }
}

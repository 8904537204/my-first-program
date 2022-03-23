pipeline {
  agent any
  stages {
    stege {'version info'} {
      steps {
        sh 'mvn --version'
        sh 'mvn clean install'
      }
    }
  }
}

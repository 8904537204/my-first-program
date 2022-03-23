pipeline {
  agent { docker { image 'maven 3.3.3'} }
  stages {
    stege {'log version info'} {
      steps {
        sh 'mvn --version'
        sh 'mvn clean install'
      }
    }
  }
}

pipeline {
  agent {label 'linux'}
  options {
    buildDiscarder (logRotator( numToKeepStr: '5'))
     disableConcurrentBuilds()
  }
  stages {
    stage('Hello') {
      steps {
        echo 'Helllo Linh'
      }
    }
  }
}
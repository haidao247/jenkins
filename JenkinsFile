pipeline {
  agent {label 'linux'}
  options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactDaysToKeepStr: '5', daysToKeepStr: '',
     numToKeepStr: '5')
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
pipeline {
  agent any
  stages {
    stage('buzz built') {
      steps {
        echo 'my first one'
      }
    }

    stage('buzz test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}
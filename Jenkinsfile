pipeline {
  agent {
    node {
      label 'Tho'
    }

  }
  stages {
    stage('Clone') {
      steps {
        sh './jenkins/build.sh'
      }
    }

  }
}
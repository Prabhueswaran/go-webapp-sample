pipeline {
  agent {
    node {
      label 'ubuntuagent'
    }

  }
  stages {
    stage('Dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}
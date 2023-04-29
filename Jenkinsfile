pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh '''skaffold build --default-repo=pmyne
'''
      }
    }

  }
}
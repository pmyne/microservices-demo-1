pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh 'skaffold build --default-repo=pmyne/onlineboutique'
      }
    }

  }
}
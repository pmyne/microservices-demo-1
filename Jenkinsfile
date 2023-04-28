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
        sh '''docker build -t cartservice-image ./scr/cartservice/scr
cd src/cartservice && dotnet build'''
      }
    }

  }
}
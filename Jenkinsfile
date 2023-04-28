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
        sh 'cd src/cartservice && dotnet build'
      }
    }

  }
}
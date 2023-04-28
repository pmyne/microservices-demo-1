pipeline {
  agent {
    docker {
     image 'microsoft/dotnet:sdk'
    }
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

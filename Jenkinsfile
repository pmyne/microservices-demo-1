pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh 'cd src/cartservice && dotnet build'
      }
    }

  }
}

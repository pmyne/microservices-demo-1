pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh 'sh \'cd /src/cartservice && dotnet build\''
        sh 'echo "Current workspace: ${WORKSPACE}"'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'echo "Current workspace: ${WORKSPACE}"'
        sh 'sh \'cd /src/cartservice && dotnet build\''
      }
    }

  }
}
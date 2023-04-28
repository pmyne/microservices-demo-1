pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'sh \'pwd\''
        sh 'sh \'cd cartservice && dotnet build\''
      }
    }

  }
}
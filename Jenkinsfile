pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh 'echo "Current workspace: ${WORKSPACE}"'
        sh '''sh \'$pwd && cd src/cartservice && dotnet build\'
'''
      }
    }

  }
}
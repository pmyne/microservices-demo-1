pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh '''sh \'cd scr/cartservice && dotnet build\'
'''
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh '''echo "Current workspace: ${WORKSPACE}"
sh \'ls\' '''
        sh '''sh \'cd scr/cartservice && dotnet build\'
'''
      }
    }

  }
}
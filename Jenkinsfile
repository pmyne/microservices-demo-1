pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh 'echo "Current workspace: ${WORKSPACE}"'
        sh '''sh \'cd /var/lib/jenkins/workspace/Online_boutique_main/cartservice && dotnet build\'
'''
      }
    }

  }
}
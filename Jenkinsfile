pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        sh '''echo "Current workspace: ${WORKSPACE}"
echo ls'''
        sh 'sh $pwd'
      }
    }

  }
}
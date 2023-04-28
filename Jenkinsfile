pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'sh \'pwd\''
        sh '''sh \'\'\'
export GOPATH=microservices-demo-1/go
cd $WORKSPACE/src/github.com/pmyne/frontend
go build -o app
\'\'\''''
      }
    }

  }
}
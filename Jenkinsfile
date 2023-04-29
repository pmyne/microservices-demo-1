pipeline {
  agent any
  environment {
	SKAFFOLD_DEFAULT_REPO = 'docker.artifactory.liatr.io/liatrio'
}
  stages {
    stage('Build') {
      steps {
        echo 'Build Start'
        container('skaffold') {
    	script {
      	docker.withRegistry("https://${SKAFFOLD_DEFAULT_REPO}", 'artifactory-credentials') {                     
         echo 'skaffold build start'
          sh "skaffold build"
      }
         
      }
    }

  }
}

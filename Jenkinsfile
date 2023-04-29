pipeline {    
	agent any 
environment {
	SKAFFOLD_DEFAULT_REPO = 'docker.artifactory.liatr.io/liatrio'
}
stages {
	stage('Build') {
  	steps {
    	// Create sonar.properties for sonar maven plugin withCredentials([string(credentialsId: 'sonarqube', variable: 'sonarqubeToken')]) {   
      //sh "echo 'sonar.login=${sonarqubeToken}' >> sonar.properties"
    //}
    // Create and test image with skaffold
    container('skaffold') {
    	script {
      	docker.withRegistry("https://${SKAFFOLD_DEFAULT_REPO}", 'artifactory-credentials') {                      
          sh "skaffold build"
      }
    }
  }
}
}
}

node {
	stage('SCm Checkout') {
	  
		git 'https://github.com/rajugsk/maven-project1'
	
	}
	
	stage('Compile-package') {
	  def mvnHome = tool name: 'maven3', type: 'maven'
	  chmod +x ${mvnHome}/bin/mvn
	  sh"${mvnHome}/bin/mvn package"
	
	}


}

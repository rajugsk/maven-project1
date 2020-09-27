node {
	stage('SCm Checkout') {
	  
		git 'https://github.com/rajugsk/maven-project1'
	
	}
	
	stage('Compile-package') {
	  sh'mvn package'
	
	}

	stage ('Email configuration'){
	mail bcc: '', body: 'The run is success', cc: '', from: '', replyTo: '', subject: 'testing from jenkins', to: 'tejo.raju@GMAIL.COM'
	
	}
}

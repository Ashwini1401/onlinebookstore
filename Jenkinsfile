pipeline {
    agent {
	customeWorkspace '/mnt/pipeline/'
	      }
	stages {
	  stage (Build) {
	   steps { 
	   sh 'mvn install'
	   sh 'cp /mnt/pipeline/onlinebookstore/target/*.war /mnt/server/apache-tomcat-9.0.65/webapps'
	  	  
	  }
	
}
}
}


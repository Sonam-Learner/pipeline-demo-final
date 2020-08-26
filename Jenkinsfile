pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {   
			sh "export MAVEN_HOME=/usr/local/opt/maven@3.6/apache-maven-3.6.3"
			sh "export PATH=$PATH:$MAVEN_HOME/bin"
			sh "mvn --version"
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {   
			sh "export MAVEN_HOME=/usr/local/opt/maven@3.6/apache-maven-3.6.3"
			sh "export PATH=$PATH:$MAVEN_HOME/bin"
			sh "mvn --version"
                	sh "mvn compile"   
                	sh "mvn test"          	 
            	}     	 
        	}	 
    	}
}


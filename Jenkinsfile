pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {   
			sh "export MAVEN_HOME=/usr/local/Cellar/maven/3.6.3_1/libexec"
			sh "export PATH=$PATH:$MAVEN_HOME/bin"
			sh "mvn --version"
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {   
			sh "export MAVEN_HOME=/usr/local/Cellar/maven/3.6.3_1/libexec"
			sh "export PATH=$PATH:$MAVEN_HOME/bin"
			sh "mvn --version"
                	sh "mvn compile"   
                	sh "mvn test"          	 
            	}     	 
        	}	 
    	}
}


pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {   
                	sh "maven compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {      
                	sh "maven test"          	 
            	}     	 
        	}	 
    	}
}


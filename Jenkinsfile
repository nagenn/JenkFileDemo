pipeline {	 
	agent any	
	tools {
		maven 'Mav'
		}
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	/* sh "mvn compile" */
			sh "echo Compile"
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	/* sh "mvn test" */
			sh "echo unit test"
            	}     	 
        	}	 
    	}
}

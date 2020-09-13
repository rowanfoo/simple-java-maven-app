pipeline {
    agent any
    tools{
       maven 'maven'
    }
    stages {
        stage('init') {
            steps {
				script
				{
						gv = load "script.groovy"
				
				}
               echo " Done init"
            }
        }
        
		stage('build') {
            steps {
				script
				{
						gv.buildApp()
		
				}
            }
        }	
        
        
        

    }


}

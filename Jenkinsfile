pipeline {
      agent any 
	  
	  stages {
	          stage("build"){
			steps {
			         echo 'building the file...'
				sh 'npm install'
		              }
			stage("test"){
			steps {
			         echo 'testing the file'
			
			}
			}
			stage("deploy"){
			 steps {
			         echo 'deploying the file'
			
			}	
			}
	        }
		}
}

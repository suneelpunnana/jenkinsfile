@Library('shlib')_
pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
      /*  stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
		   // metrics()
            }
        }*/
        stage('Deploy') {
            steps {
                UserDetails(JSON)
		    score(JSON)
		
		  
            }
	}

	    
	    /*stage('deliver'){
			steps{
				username()
			}
		}*/
    }

}
   




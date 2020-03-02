@Library('shlib')_
pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                test()
		
		  //  testbuild()
            }
	}
	    
	    
	    /*stage('deliver'){
			steps{
				username()
			}
		}*/
    }
}
   

	

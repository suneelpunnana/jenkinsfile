pipeline {
	libraries{
lib 'shlib'
	}
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
                Build()
            }
	
	
        }
    }
}
   

	

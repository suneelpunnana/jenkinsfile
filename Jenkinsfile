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
                echo 'Deploying'
            }
		stage('check')
		steps{
			sh "curl -XGET -g http://52.14.229.175:8080/job/'${jobname}'/api/json?tree=builds[number,status,timestamp,id,result] -u admin:jenkins latest api:11035ac86f58bc32d03d8e873b7cc063a3"
		}
        }
    }
}
   

	

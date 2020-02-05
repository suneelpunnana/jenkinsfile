@Library('shlib')_
pipeline{
agent any
stages{
	stage('Test Stage'){
		steps{
			collector()
			
		}}
		stage('build'){
		steps{
			Build("jersey")
		}}
	
	
	stage('build'){
		steps{
			consoleoutput()
		}}
	
	
		}
}
	

pipeline{
agent any
stages{
	stage('Test Stage'){
		steps{
			collector()
			
		}}
		stage('build'){
		steps{
			Build()
		}}
	
	
	stage('test'){
		steps{
			consoleoutput()
		}}
	
	stage('deploy'){
		steps{
			pluginlist()
		}}
			
	
		}
}
	

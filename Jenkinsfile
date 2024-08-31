pipeline 
{
	agent any
	tools
	{
		maven 'MAVEN_HOME'
	}
	
	stages{
		stage('Welcome Stage')
		{
			steps
			{
				echo 'Welcome to Jenkins Pipeline'
			}			
		}
		stage('Clean Stage')
		{
			steps
			{
				bat 'mvn clean'
			}			
		}
		stage('Build Stage')
		{
			steps
			{
				bat 'mvn install'
			}			
		}
		stage('Java Version Check Stage')
		{
			steps
			{
				bat 'java --version'
			}			
		}
		stage('Test Stage')
		{
			steps
			{
				bat 'mvn test'
			}			
		}
		stage('Success Stage')
		{
			steps
			{
				echo 'Successfully Build Thanks'
			}			
		}
	
	}
}
pipeline{
	agent any
	environment
	{
	    scannerHome = tool name: 'sonar_scanner_dotnet',type :'hudson.plugins.sonar.MsBuildSQRunnerInstallation'
	}
	stages
	{
		stage('checkout')
		{
			steps
			{
				checkout scm
			}
		}
		

	}
}
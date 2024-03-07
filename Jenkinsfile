pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/ramyachetty/maven.git"
				}
			}
		stage("run")
			{
			steps
				{
				sh "mvn clean"
				}
			}
		}
	}

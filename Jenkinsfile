pipeline 
	{
		
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/SreekanthJaladanki/Jenkins_practice.git"
				}
			}
		stage("run")
			{
			steps
				{
				sh "java Demo.java"
				}
			}
		}
	}

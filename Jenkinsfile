pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/kirangowdaN/Ubuntu_jenkins.git"
				}
			}
		stage("run")
			{
			steps
				{
				sh "java demo.java"
				sh "python3 main.py"
				}
			}
		}
	}

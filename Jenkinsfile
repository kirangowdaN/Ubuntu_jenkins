pipeline 
	{	
	agent {
		label "s1"
	}
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/Lohithreddy-k/task0226.git"
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

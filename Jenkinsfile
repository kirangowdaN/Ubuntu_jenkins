pipeline 
	{	
	agent {
		lable "us1"
	}
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/Lohithreddy-k/Ubuntu_jenkins.git"
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

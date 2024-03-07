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
				git branch: 'main', url: 'https://github.com/ramyachetty/maven.git'
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

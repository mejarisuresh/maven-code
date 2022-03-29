pipeline{
	agent any
	stages{
		stage {
			stage("maven build")
			{
				when {
					branch 'devlop'
				}
				steps {
					sh 'mvn clean package'
				}
			}
		}
	}

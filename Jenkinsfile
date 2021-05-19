pipeline {
agent any
stages {
	stage('Init')	 {
		steps {
			echo 'Hi, This is Ashish'
			echo 'We are Starting the Testing'
		}
	}
        stage('Build')    {
                steps {
                        echo 'Building Sample Maven Project'
                }
        }
        stage('Deploy')    {
                steps {
                        echo 'Deploying in Stagging Area'
                }
        }	
	}
}

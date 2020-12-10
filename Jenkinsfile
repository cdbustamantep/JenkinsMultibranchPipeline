pipeline {
	agent any
		stages {
			
			
			
			stage('First') {
				environment {
                			EXECUTE = "True"
            			}
			}
			

		
			stage('Second') {
				steps { 
					sh 'echo "updating second stage"'
					sh 'echo "EXECUTE = ${env.EXECUTE}"'
				}
			}
			     			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


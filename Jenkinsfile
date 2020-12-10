pipeline {
	agent any
		stages {
			
			
			
			stage('First') {
				steps { sh ' env EXECUTE="True" '
				}
			}
			

		
			stage('Second') {
				steps { 
					sh 'echo "updating second stage"'
					sh 'echo $EXECUTE'
				}
			}
			     			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


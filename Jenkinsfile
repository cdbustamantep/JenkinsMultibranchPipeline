pipeline {
	agent any
		stages {
			
			
			
			stage('First') {
				steps { sh ' env EXECUTE="True" '
				}
			}
			
			When { EXECUTE=="True"
			      
			      stage('Second') {
					steps { sh 'echo "updating second stage"'
					}
				}
			     }
			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


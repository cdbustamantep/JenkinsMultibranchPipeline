pipeline {
	agent any
		stages {
			
			
			
			stage('First') {
				steps {
					script {
						env.VARIABLE="value"
					 }
				 }
			}
			

		
			stage('Second') {
				steps { 
					sh 'echo "updating second stage"'
				}
			}
			     			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


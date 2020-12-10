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
					script {
						echo ${VARIABLE}
					 }
				}
			}
			     			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


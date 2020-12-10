pipeline {
	agent any
		stages {
			
			
			
			stage('First') {
				steps {
					script {
						env.EXECUTE="False"
					 }
				 }
			}
			


			stage('Second') {
				when { 
					expression { return EXECUTE == "True" } 
				}
				steps { 
					sh 'echo "updating second stage"'
					echo "$EXECUTE"
				}
			}
			     			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


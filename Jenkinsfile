pipeline {
	agent any
		stages {
			
			
			
			stage('First') {
				steps {
					script {
						env.EXECUTE="True"
					 }
				 }
			}
			

			when { $EXECUTE=="True"
			     }
				stage('Second') {
					steps { 
						sh 'echo "updating second stage"'
						script {
							echo "$EXECUTE"
						 }
					}
				}
			     			
				
			
			
			stage('Third') {
				steps { sh 'echo "Step Three"'
				}
			}
			
			
			
		}
}


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
			


				stage('Second') {
					when { $EXECUTE=="True" }
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


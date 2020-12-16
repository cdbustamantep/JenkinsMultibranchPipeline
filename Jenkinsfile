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
				when { 
					expression { return EXECUTE == "True" } 
				}
				steps { 
					sh 'echo "updating second stage1"'
				}
			}
			stage('Third') {
				when { 
					expression { return EXECUTE == "False" } 
				}
				steps { sh 'echo "Step Three"'
				}
			}	
		}
}


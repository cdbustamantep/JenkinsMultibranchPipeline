pipeline {
	agent any
		stages {
			stage('First') {
				steps { sh 'env.EXECUTE="True"'
				}
			}
			when { $(EXECUTE) == "True" }
			steps {
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


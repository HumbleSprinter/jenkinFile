pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac class1.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java class1"""
				}
			}
			
		}
	}

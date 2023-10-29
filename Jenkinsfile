pipeline {
	agent any 
	stages {
	
		stage("build") {
			steps {
			sh '''#!/bin/bash
   			ansible-playbook "${WORKSPACE}/main.yml"'''
			
			}
			
		
		}

		
	
	
	}




}

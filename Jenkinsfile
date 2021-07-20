pipeline {
	agent none  
	stages {
		stage('BUILD') {
      agent {label 'mast'}
			steps {
				sh '''
					pwd
					sleep 5
					echo This is the fist stage: BUILD
				'''
			}	
		}
		
		stage('TEST') {
      agent {label 'tag'}
			steps {
				sh '''
					pwd
					sleep 5
					echo This is the fist stage: TEST
				'''
			}	
		}
		
		stage('DEPLOY') {
      agent {label 'mast'}
			steps {
				sh '''
					pwd
					sleep 5
					echo This is the fist stage: DEPLOY
				'''
			}	
		}
	}
}

pipeline{agent any 
    tools {
     		gradle "gradle-4.0"
    }
    stages{
       stage('SCM'){
	       steps{
		       git credentialsId: 'db2e434e-c6c9-43a2-943d-786a2f63faba', url: 'https://github.com/jitpack/gradle-simple.git'
	       }
	}
	stage('Build'){
		steps{
			sh 'gradle --version'
		}
	}
}
}
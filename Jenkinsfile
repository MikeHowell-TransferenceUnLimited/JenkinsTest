pipeline {
  agent any
  stages {
    stage('Hello'){	
	  steps{
   	     echo 'Hello world'
	     echo 'Build number is ${currentBuild.number}'
	     echo "Build number is ${currentBuild.number}"
             sh 'echo echo "Build number is ${currentBuild.number}"'
	  }	
    }
  }
}

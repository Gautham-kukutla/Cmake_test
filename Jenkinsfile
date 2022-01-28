pipeline {
	agent any

  stages {
	  stage('Building'){
		  steps{
	    
	cmakeBuild buildDir: 'build', cleanBuild: true, installation: 'InSearchPath', steps: [[withCmake: true]]
		   }  }
  }
}

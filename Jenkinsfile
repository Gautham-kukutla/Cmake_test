pipeline {
	agent any

  stages {
	  stage('Building'){
		  steps{
	    
	cmakeBuild buildDir: 'build', cleanBuild: true, generator: 'mingw32-make', installation: 'InSearchPath', steps: [[withCmake: true]]
		   }  }}
  }
}

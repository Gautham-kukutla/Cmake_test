pipeline {
	agent any

  stages {
    stage('Building'){
	    dir('build'){
      bat "cmake .../ && cmake --build ."
	    }}
  }
}

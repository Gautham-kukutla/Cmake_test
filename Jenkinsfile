pipeline {
	agent any

  stages {
    stage('Building'){
	    steps{
	    dir('build'){
      bat "cmake .../ && cmake --build ."
	    }}}
  }
}

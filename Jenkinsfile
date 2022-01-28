pipeline {
	agent any

  stages {
    stage('Building'){
	    steps{
	    dir('build'){
      bat "cmake .../ "
      bat "cmake --build ."
	    }}}
  }
}

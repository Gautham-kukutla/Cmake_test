pipeline {
	agent any

  stages {
    stage('Building'){
	    steps{
	    dir('build'){
      bat "cmake -S ../ && cmake --B . -G 'MinGW Makefiles'"
	    }}}
  }
}

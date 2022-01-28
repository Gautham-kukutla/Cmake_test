pipeline {
	agent any

  stages {
    stage('Building'){
	    steps{
      cmake -S ../ -B . -G "MinGW Makefiles"
	    }}
  }
}

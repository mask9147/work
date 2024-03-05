pipeline{
  agent none
  stages{
    stage('Build'){
      agent any
      steps {
        cleanWS()
        echo 'Hello world'
              sh mkdir ABC
        sh ls -lart
              sh pwd
      }
    }
    stage('Test on Java') {
      agent { 
      label 'java'
            }
      steps {
        cleanWs()
        echo 'Hello World'
	      sh 'mkdir abc'
	sh 'ls -lart'
		sh 'pwd'
           }
    }
  }
}

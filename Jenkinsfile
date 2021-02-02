pipeline {
    options {
        timeout(time: 30, unit: 'MINUTES')
    }
    agent {
      node {
	label 'master'
      }
    }

    stages {
    
    	stage('SCM Checkout') {
	    	steps {
	    		checkout url: 'https://github.com/slibonati/spring-rest'
	    	}
  		}
	}
}
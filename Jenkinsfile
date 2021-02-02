pipeline {
    options {
        timeout(time: 30, unit: 'MINUTES')
    }
    
    agent any

    stages {
    	stage('checkout') {
	    	steps {
	    		git url: 'https://github.com/slibonati/spring-rest'
	    	}
  		}
	}
}
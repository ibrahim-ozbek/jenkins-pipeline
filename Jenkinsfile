pipeline {
    agent any
    stages {
       stage('build') {
           steps {
	       sh 'echo build has been started'
	       sh ' echo Integrating pipeline using Jenkinsfile and webhook'
	       sh 'ls'
	       }
	     }
	   
       stage('test') {
           steps {
	       sh 'echo new stage added'
	       sh 'echo good job bay bay'
	       }
	      }
       stage('deploy') {
           steps {
	       sh 'echo hello your application-222'
	       sh 'python --version'
	       sh 'python pipeline.py'
	       }
	    }
	 }   
	}


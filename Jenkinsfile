pipeline {
    agent any
	tools {
		maven 'Maven'
	}
	
	environment {
		PROJECT_ID = 'speedy-index-431715-p8'
                CLUSTER_NAME = 'k8s-cluster'
                LOCATION = 'us-central1-c'
                CREDENTIALS_ID = 'b7de675c-1d96-473c-86d1-1226cf2ae1c8'		
	}
	
    stages {
	    stage('Scm Checkout') {
		    steps {
			    checkout scm
		    }
	    }


}

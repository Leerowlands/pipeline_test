pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'This is a change'
            }
        }
        stage('test'){
            steps {
                echo 'This is a test stage'
            }
        }
	stage('deploy'){
	    steps {
	        echo 'This is a deploy stage'
	    }	
	}

    }
}

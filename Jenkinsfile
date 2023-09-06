pipeline {
	agent any

	stages {
	  stage(build) {
	    steps {
	      echo "Buildddiddddng the app.."
	    }
	  }
	  stage(test) {
	    steps {
	       echo "Testingggg the app.."
	    }
	  }
  	  stage(Deploy) {
            steps {
               echo "Finallyier231Update Deploying the app.."
	       script {
		       sh "java -V && echo "success" || exit 1"
	       }
            }
          }
	}
	  post {
		  success {
			  echo " build got success"
		  }
	  }
  }



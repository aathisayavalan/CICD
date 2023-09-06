pipeline {
	agent any

	stages {
	  stage(build) {
	    steps {
	      echo "Building the app.."
	    }
	  }
	  stage(test) {
	    steps {
	       echo "Testing the app.."
	    }
	  }
  	  stage(Deploy) {
            steps {
               echo "Update Deploying the app.."
            }
          }
  }
}


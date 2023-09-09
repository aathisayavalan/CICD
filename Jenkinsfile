pipeline {
	agent any
	paramaters {
	    choice(name: 'ENV', choices: ['dev', 'qa'], description: '')
	}
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
	  stage(selected Env){
            steps {
		echo "env is ${ENV}"
		  }
	  }
  	  stage(Deploy) {
            steps {
               echo "Finallyidder231Update Deploying the app.."
            }
          }
  }
}


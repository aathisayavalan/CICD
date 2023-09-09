pipeline {
    agent any
    parameters {
        choice(name: 'ENV', choices: ['dev', 'qa'], description: '')
    }
    stages {
        stage('Build') {
            steps {
                echo "Building the app.."
            }
        }
        stage('Test') {
            steps {
                echo "Testing the app.."
            }
        }
        stage('Selected Env') {
            steps {
                echo "Environment is ${ENV}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the app.."
            }
        }
    }
}

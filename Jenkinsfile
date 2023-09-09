pipeline {
    agent any
    parameters {
        choice(name: 'ENV', choices: ['dev', 'qa'], description: '')
    }
    environment {
        git_username = credentials('github')
    }
    stages {
        stage('Build') {
            steps {
                echo "Building the app.."
                echo "git username ${git_username}"
            }
        }
        stage('Test') {
            steps {
                echo "Testing the app.."
            }
        }
        stage('Selected Env') {
            steps {
                echo "Environment is ${params.ENV}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the app.."
            }
        }
    }
}

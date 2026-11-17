pipeline {
    agent any
    
    tools {
        maven : 'Maven'
        }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins!'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
            }
        }
    }
}

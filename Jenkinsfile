pipeline {
    agent any

    stages {
        stage('First Stage') {
            steps {
                echo 'Running on Java agent'
            }
        }

        stage('Second Stage') {
            steps {
                sh 'java -version'
            }
        }

        stage('Third Stage') {
            steps {
                echo 'Pipeline completed successfully!'
            }
        }
    }
}

pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage('Welcome Step') {
            	when {
    environment name: 'DEPLOY_TO', value: 'production'
}
            steps {
                echo 'Welcome to LambdaTest'
            }
        }
    }
}

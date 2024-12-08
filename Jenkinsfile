pipeline {
agent { label 'agent' }
stages {
    stage('Build') {
        steps {
            echo 'Building the app on agent without container....'
            }
    }
    stage('Test') {
        steps {
            echo 'Testing the app.....'
            }
    }
    stage('Deploy') {
        steps {
            echo 'Deploying the app....'
        }
    }
}
}
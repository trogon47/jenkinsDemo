pipeline {
    agent { 
        node {
            label 'builtin'
            }
      }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh 'echo hello'
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
            }
        }
    }
}
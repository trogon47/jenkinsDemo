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
                sh 'ls'
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
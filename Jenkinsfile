pipeline {
    agent {
        node{
            label 'AGENT1'
        }
    stages {
        stage ('build') {
            steps {
                echo 'Building the application'
                sh "echo 'Building the application' >> /tmp/jenkins.log"
            }
        }
    }
    }
    
}
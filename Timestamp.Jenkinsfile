pipeline {
    agent {
        label "master"
    }
    stages {
        stage ('Build') {
            options {
                timestamps()
            }
            steps {
                echo "Build stage"
            }
        }
        stage ('Test') {
            steps {
                echo "Test Stage"
            }
        }
    }
}
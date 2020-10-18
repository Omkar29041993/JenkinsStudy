pipeline {
    agent {
        label "master"
    }
    stages{
        stage ('Build'){
            tools {
                maven 'Maven3'
            }
            steps{
                sh 'mvn --version'
            }
        }
    }
}
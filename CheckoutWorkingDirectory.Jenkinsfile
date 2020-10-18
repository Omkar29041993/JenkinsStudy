pipeline{
    agent{
        label "master"
    }
    options {
        checkoutToSubdirectory('Omkar')
    }
    stages{
        stage("A"){
            steps{
                echo "Current working directory"
                sh 'pwd'
            }
        }
    }
}
pipeline{
    agent{
        label "master"
    }
    stages{
        stage("A"){
            options {
                checkoutToSubdirectory('Omkar')
            }
            steps{
                echo "Current working directory"
                sh 'pwd'
            }
        }
    }
}
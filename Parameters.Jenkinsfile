pipeline{
    agent{
        label "master"
    }
    parameters {
        string(name: 'PARAM1', description:  'Param1')
    }
    stages{
        stage("A"){
            steps{
                echo "PARAM1=$PARAM1"
            }
        }
    }
}
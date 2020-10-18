pipeline{
    agent{
        label "master"
    }
    stages{
        stage("A"){
            steps{
                timeout(time: 10, unit: "SECONDS")
                {
                    echo "Sleeping in timeout"
                    sleep 20
                }
            }
        }
    }
}
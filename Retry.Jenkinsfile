pipeline{
    agent{
        label "master"
    }
    stages{
        stage("A"){
            steps{
                retry (3)
                {
                    echo "Before Throwing error"
                    echo "error in the retry"
                }
                echo "After Retry 3"
            }
        }
    }
}
pipeline{
    agent{
        label "master"
    }
    stages{
        stage ('Parallel Stage') {
            failFast true
            parallel {
                stage("Stage1"){
                    steps{
                        echo "stage1" 
                        sleep 10  
                    }
                }
                stage("Stage2"){
                    steps{
                        echo "Stage2"
                        sleep 10
                    }
                }
                stage("Stage3"){
                    steps{
                        echo "Stage3"
                        sleep 10
                    }
                }
            }
        }    
    }   
}   
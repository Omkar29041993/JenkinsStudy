pipeline{
    agent{
        label "master"
    }
    environment {
        name1="Omkar"
        name2="Sachin"
    }
    stages{
        stage("Build"){
            environment {
                name3="Vivek"
            }
            steps{
              echo "name1=$name1"
              echo "name2=$name2"
              echo "name3=$name3"  
            }
        }
        stage("Test"){
            environment {
                name3="Anil"
            }
            steps{
              echo "name1=$name1"
              echo "name2=$name2"
              echo "name3=$name3" 
            }
        }

        stage ("PrintEnv")
        {
            steps {
                sh 'printenv'
            }
        }
    }
}
pipeline{
    agent{
        label "master"
    }
    stages{
        stage("Build"){
            steps{
                echo "========executing A========"
            }
            post{
                always{
                    echo "Build Stage- Always"
                }
                success{
                    echo "Test Stage- Success"
                }
                failure{
                    echo "Test Stage-Failure"
                }
            }
        }
        stage ("Test"){
            steps{
                echo "Test Stage"
            }
            post {
                always{
                    echo "Test Stage- Always"
                }
                success{
                    echo "Test Stage- Success"
                }
                failure{
                    echo "Test Stage-Failure"
                }
            }
        }
    }
 
    post{
        always{
            echo "Post Build Stage- Always"
        }
        success{
            echo "Post Build Stage- Success"
        }
        failure{
            echo "Post Build Stage- Failure"
        }
    }
}
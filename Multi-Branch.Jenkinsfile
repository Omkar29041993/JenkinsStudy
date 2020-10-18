pipeline{
    agent{
        label "master"
    }
    stages{
        stage("Build-Master"){
            when {
                branch 'master'
            }
            steps{
                echo "master branch"
            }
        }
        stage("Build-Dev"){
            when {
                branch 'dev'
            }
            steps{
                echo "dev branch"
            }
        }
    }
}
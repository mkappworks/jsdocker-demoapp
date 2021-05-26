pipeline{
    agent any

    stages{
        
        
        stage("build"){
            steps{
                echo 'building the application...'
                echo 'excuting yarn...'
                nodejs('Node-10.17'){
                    sh 'yarn install'
                }
                echo 'application built!'
            }
        }

        stage("test"){
            steps{
                echo 'testing the application...'
            }
        }

        stage("deploy"){
            steps{
                echo 'deploying the application...'
            }
        }
    }
}

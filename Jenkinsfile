pipeline{
    agent any
    stages{
        stage("One"){
            steps{
                echo "Stage 1 step1"
            }
        }
        stage("Two"){
            steps{
                echo "Stage 2 step2"
            }
        }
        stage("Three"){
            steps{
                echo "Stahe 3 step 1"
            }
        }
    }
    post{
        always{
            echo "====++++always++++===="
        }
        success{
            echo "====++++only when successful++++===="
        }
        failure{
            echo "====++++only when failed++++===="
        }
    }
}
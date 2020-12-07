pipeline{
    agent any
    environemt{
        VAR=9000123
    }
    stages{
        stage("build"){
            steps{
                echo "building123.."
                echo "${VAR}"
            }
        }
        stage("test"){
            steps{
                echo "testing123.."
            }
        }
        stage("deploy"){
            steps{
                echo "deploying123.."
            }
        }
    }
}

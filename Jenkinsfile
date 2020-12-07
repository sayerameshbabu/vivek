pipeline{
    agent any
    environment{
        VAR=9000123
    }
    parameters{
        string(name: 'VERSION', defaultValue: '1.0', description:'this is the default value for version')
    }
    tools{
        maven 'Maven1'
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
                echo "${VERSION}"
            }
        }
        stage("deploy"){
            steps{
                echo "deploying123.."
                mvn clean install
            }
        }
    }
}

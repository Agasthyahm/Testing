pipeline{
    agent any
    stages{
        stage("branch name"){
            steps{
                echo "Branch is ${env.GIT_BRANCH}"
            }
        }
        stage("deploy-main"){
            when{
                expression {env.GIT_BRANCH == 'origin/main'}
            }
            steps{
                sh "echo deploying to main"
            }
        }
        stage("deploy-test"){
            when{
                expression {env.GIT_BRANCH == 'origin/test'}
            }
            steps{
                sh "echo deploying to test"
            }
        }
                
    }
}

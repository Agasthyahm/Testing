pipeline{
    agent any
    environment{
        MY_ENV="${BRANCH_NAME}"
    }
    stages{
        stage("branch name"){
            steps{
                echo "Branch is ${env.GIT_BRANCH}"
                echo "Branch is ${MY_ENV}"
            }
        }
    }
}

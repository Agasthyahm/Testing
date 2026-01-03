pipeline{
    agent any
    environment{
        BRANCH_ENV="${BRANCH_NAME}"
    }
    stages{
        stage("branch name"){
            steps{
                echo "Branch is ${BRANCH_ENV}"
            }
        }
    }
}

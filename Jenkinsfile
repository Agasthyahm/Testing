pipeline{
    agent any
    environment{
        BRANCH_ENV="${BRANCH_NAME}"
    }
    stages{
        stage('SCM'){
            steps{
                git url: "https://github.com/Agasthyahm/Testing.git"
            }
        }
        stage("branch name"){
            steps{
                echo "Branch is ${BRANCH_ENV}"
            }
        }
    }
}

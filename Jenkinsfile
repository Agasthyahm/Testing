pipeline{
    agent any
    stages{
        stage('Checkout') {
            steps {
                git branch:"main", url:"https://github.com/Agasthyahm/Testing.git"
            }
        }
        stage("branch name"){
            steps{
                echo "Branch is ${env.GIT_BRANCH}"
            }
        }
    }
}

pipeline{
    agent any
    stages{
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage("branch name"){
            steps{
                echo "Branch is ${env.GIT_BRANCH}"
            }
        }
    }
}

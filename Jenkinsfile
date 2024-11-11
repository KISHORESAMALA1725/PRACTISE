
pipeline {
    agent any 
    stages{
        stage ('this is expression stage') {
            steps{
                when {
                    expression ==~ /(feature|hotfix)/
                }
                echo "this stage is executed"
            }
        }
    }
}

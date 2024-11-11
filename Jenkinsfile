pipeline {
    agent any 
        stages {
            stage ('this is error stage') {
                steps {
                    echo " **** THIS WILL ERROR OUT"
                    error " ORA-01555"
                }
            }
        }
}

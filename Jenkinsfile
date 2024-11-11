pipeline {
    agent any
    stages {
        stage ("this is retry stage") {
            steps {
                retry (3){ 
                echo " **** RETRYING ****"
                error "JOB FAILED AFTER RETRY"
            }
        }
    }
}

}

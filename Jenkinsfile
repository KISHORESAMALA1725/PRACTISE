pipeline {
    agent any
    stages {
        stage ('This is timeout stage example') {
            steps {
                timeout(TIME: 10, UNIT: "SECONDS") {
                    echo " ******* TIME-OUT, PLEASE TRY AGAIN"
                    sleep 60
                }
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage ('This is timeout stage example') {
            steps {
                timeout(time: 10, unit: "SECONDS") {
                    echo " ******* TIME-OUT, PLEASE TRY AGAIN"
                    sleep 60
                }
            }
        }
    }
}

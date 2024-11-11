pipeline {
    agent any
    stages {
        stage ('This is time-out example') {
            timeout (time: 10, unit: 'SECONDS')
            echo " TIMEOUT OVERWRITES  SLEEP"
            sleep 30
        }
    }
}

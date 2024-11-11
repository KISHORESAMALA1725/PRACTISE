pipeline {
    agent any
    stages{
        stage ('this is timeout example') {
            steps {
                timeout (time: 10, unit: 'SECONDS') {
                echo " *** This is time-out example"
                sleep 30
                }
            }
        }
    }
}

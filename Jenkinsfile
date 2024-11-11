pipeline {
    agent any
    environment {
       MY_CREDS = credentials('java-slave-siva-creds')
    }
    stages {
        stage ('this is credentials example') {
            steps {
                echo "username is ${MY_CREDS_USR}"
                echo "password is ${MY_CREDS_PSW}"
            }
        }
    }
}

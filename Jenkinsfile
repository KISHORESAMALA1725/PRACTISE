pipeline {
    agent {
        label 'java-slave'
    }
    tools {
        maven 'maven-3.8.8'
    }
    stages{
        stage ('This is maven-stage') {
            steps {
                sh 'mvn -version'
            }
        }
        stage ('MVN AUTOINSTALLER') {
            tools {
                maven 'maven-autoinstaller'
                jdk 'JDK-17'
            }
            steps {
                sh 'mvn -version'
                sh 'java -version'
            }
        }


    }
}



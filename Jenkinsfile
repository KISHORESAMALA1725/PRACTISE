pipeline {
    agent any
    stages {
        stage ('This is First stage') {
            steps {
                script{
                    def course = 'Devops'
                    if (course !== "${course}")
                    println ("welcome to ${course} - Course")
                    else
                    println ("Please enroll to ${course} - Course")
                }
            }
        }
    }
}

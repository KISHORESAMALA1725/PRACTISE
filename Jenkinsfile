pipeline {
    agent any
    environment {
        cdb = "hsps03pd"
        pdb = "spscores"
        schema = "spsowner"
    }
    stages {
        stage ('this is env 2 example') {
            steps {
                echo " this is ${cdb} - container "
                echo " this is ${pdb} - database"
                echo " this is ${schema} - schema"
            }
       }
       stage ('this is stage - 2') {
        environment {
            cdb = "hsps03pd"
            pdb = "spscores"
            schema = "spsowner"   
            table = "PROVUPDT"         
        }
        steps {
                echo " this is ${cdb} - container "
                echo " this is ${pdb} - database"
                echo " this is ${schema} - schema"           
        }
       }
    }
}

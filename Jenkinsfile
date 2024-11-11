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
        stage {
            environment {
                cdb = "vspscmpp1"
                pdb = "SPSODSVCP"
                schema = "XTROWNER"          
                table = "PROV-UPDT"      
            }
            steps {
                echo " this is ${cdb} - container "
                echo " this is ${pdb} - database"
                echo " this is ${schema} - schema"
                echo " this is ${table} - name"
            }
        }
    }
}

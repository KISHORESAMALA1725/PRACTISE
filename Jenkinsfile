pipeline {
    agent any
    environment {
        cdb = 'hsps03pd'
        pdb = 'spsocres'
        schema = 'spsowner'
    }
    stages {
        stage ('this is env stage') {
            steps {
                echo "CDB name is ${cdb}"
                echo "pdb name is ${pdb}"
                echo "schema name is ${schema}"
            }
        }
    }
}

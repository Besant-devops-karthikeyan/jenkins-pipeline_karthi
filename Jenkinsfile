
pipeline {

    agent {
        node {
            label 'SLAVE01'
        }
    }
    stages {
        
        stage('Cleanup Workspace') {
            steps {
                sh """
                echo "Cleaned Up Workspace for App"
                """
            }
        }


        stage('Code Build') {
            steps {
                 echo 'Code Build'
            }
        }

        stage('Priting All Global Variables') {
            steps {
                sh """
                echo "Priting All Global Variables"
                """
            }
        }

    }   
}

pipeline {
    agent any
    environment{

        MY_CREDS = credentials('rowan-cred')


    }

    stages {
        stage('Build') {
            steps {
            }
        }
       stage('SHOW') {
            steps {
                echo " creds ---  ${MY_CREDS}"
                echo " creds ---  ${MY_CREDS_USR}"
                echo " creds ---  ${MY_CREDS_PSW}"


            }
        }



    }


}

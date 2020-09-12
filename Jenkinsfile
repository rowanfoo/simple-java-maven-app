pipeline {
    agent any
    environment{

        MY_CREDS = credentials('rowan-cred')


    }

    stages {
        stage('Build') {
            steps {
                echo " creds ---  ${MY_CREDS}"

            }
        }
       stage('SHOW') {
            steps {
                echo " credsA ---  ${MY_CREDS_USR}"
                echo " credsB ---  ${MY_CREDS_PSW}"


            }
        }



    }


}

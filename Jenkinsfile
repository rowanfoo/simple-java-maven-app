pipeline {
    agent any
    tools{
       maven 'maven'
    }
    stages {
        stage('Build') {
            steps {
              sh "mvn clean"

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

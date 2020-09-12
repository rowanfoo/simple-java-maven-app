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
                echo " credsA ---  HELLO WORLD"
                


            }
        }



    }


}

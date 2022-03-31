pipeline {
    agent any
    environment{
       ENV-URL= "pipeline.google.com"
       SSH_CRED= credentials{"SSH"}
       }
    stages {
        stage{'one'} {
            steps {
                echo 'one'
                echo ENV-URL = ${ENV_URL}
            }
        }
        stage{'two'} {
             steps {
                 echo 'two'
             }
        }
    }
}

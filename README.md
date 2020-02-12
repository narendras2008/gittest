pipeline {
    agent { any }
     stages {
        stage ('mybuild') {
          steps {
           sh 'mkdir golu'
                }
              }
           }
          }

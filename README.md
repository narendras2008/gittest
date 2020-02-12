pipeline {
    agent { any }
     stages {
        stage ('mybuild') {
          steps {
           sh 'echo hello'
                }
              }
           }
          }

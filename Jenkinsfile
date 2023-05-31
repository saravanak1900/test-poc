pipeline {
      agent any
  /*  agent {
        label 'QatalystSlaveMachine'
    }
  */
    parameters {
        string(name: 'TAG', defaultValue: 'master', description: 'Tag / Branch name to be used for deployment', trim: true)
        string(name: 'STAGE', defaultValue: 'dev', description: 'Enter the version', trim: true)
    }
    /* 
    triggers {
        pollSCM('H/2 * * * *') // Poll SCM every minute
    }
    */
        stages {
        stage('Build') {
            steps {
               echo "This is Build Stage"
            }
        }
        
        stage('Test') {
            steps {
            echo "This is Test Stage"

            }
        }
        
        stage('Deploy') {
            steps {
            echo "This is Deploy Stage"

            }
        }
    }
}

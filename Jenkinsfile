pipeline {
    agent any
    stages {
        steps {
            sh '''
            echo "PATH = ${PATH}"
            echo "M2_HOME" = ${M2_HOME}
            '''
        }
    }

    stage ('Build'){
        steps {
              echo 'Hello World'
        }
    }


}

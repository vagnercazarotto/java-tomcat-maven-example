pipeline {
    agent any
    stages {

        stage ('Build in Staging Area'){
            steps{
                sh 'mvn clean package'
            }



        post{
            success{
                echo 'Now Archiving....'

                archiveArtifacts artifacts : '**/*.war'
                }
            }

        }
    }
}

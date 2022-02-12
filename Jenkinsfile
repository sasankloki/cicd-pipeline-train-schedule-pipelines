pipeline {
    agent any
    stages {
        stage ('build'){
            steps {
                echo 'running build automations'
                sh './gradelew build --no-deamon'
                archiveArfifact artifact: 'dist/trainSchedule.zip'

            }
        }
    }
}
  

pipeline {
    agent any
    stages {
        stage ('build'){
            steps {
                echo 'running build automations'
                sh './gradlew build --no-daemon'
                archiveArfifact artifact: 'dist/trainSchedule.zip'

            }
        }
    }
}
  

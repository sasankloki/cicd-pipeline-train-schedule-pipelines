pipeline {
    agent any
    stages {
        stage ('build'){
            steps {
                echo 'running build automations'
                sh './gradlew build --no-daemon'
                archiveArtifact artifact: 'dist/trainSchedule.zip'

            }
        }
    }
}
  

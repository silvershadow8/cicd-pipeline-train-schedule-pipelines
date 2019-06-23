pipeline{
  agent any
  stagesP{
    stage('build'){
      steps{
        echo 'Running build automation'
        sh './gradlew build --no-daemo'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

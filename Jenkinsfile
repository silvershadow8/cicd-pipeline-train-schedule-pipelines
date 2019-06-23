pipeline{
  agent any
  stagesP{
    stage('build'){
      steps{
        echo 'Running build automation'
        sh './silvershadow8 build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

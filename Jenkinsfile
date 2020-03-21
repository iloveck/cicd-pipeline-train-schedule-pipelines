pipelline {
  agent any
  stages  {
    stage ('Build')  {
      steps {
        echo "Running build automation'
        sh './gradelewbuild --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  } 
}

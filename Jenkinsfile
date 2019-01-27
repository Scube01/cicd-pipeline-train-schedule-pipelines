pipleline{
agent any
  stages{
  stages('Build'){
    steps{
    echo'Running buildautomation'
      sh './gradlew build --nodaemon'
      archiveArtifacts artifacts :'dist/trainSchedule.zip'
    }
    }
  }
}

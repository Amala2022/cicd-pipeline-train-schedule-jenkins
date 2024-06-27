pipeline{
  agents any
  stages{
    stage ('Build'){
     steps { 
       echo 'Build automation started'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainShedule.zip'
    }
    }
  }
}

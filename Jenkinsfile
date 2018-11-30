pipeline {
agent any
 stages {
  stage('Build') {
    echo 'Build stage started'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
   }
 }
}

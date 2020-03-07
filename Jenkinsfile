node {
   stage('Build') {
      sh "gradlew build"
   }
   stage('Archive') {
      archive 'dist/trainSchedule.zip'
   }
}

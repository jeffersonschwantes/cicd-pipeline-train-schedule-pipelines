node {
   stage('Build') {
      sh "./gradew build"
   }
   stage('Archive') {
      archive 'dist/trainSchedule.zip'
   }
}

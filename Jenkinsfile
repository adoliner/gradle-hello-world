#!groovy
node('slave1') {
   stage ('Checkout'){
      checkout scm
      
   }

   stage ('Build gradle'){
      def gradleHome = tool 'gradle4'
      sh "${gradle4}/bin/gradle clean jar"
   }
}

#!groovy
node('slave1') {
   stage ('Checkout'){
      checkout master
      
   }

   stage ('Build gradle'){
      def gradleHome = tool 'gradle4'
      sh "${gradleHome}/bin/mvn gradle build"
   }
}

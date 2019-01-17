#!groovy
node('slave1') 
 gradle4 = tool 'gradle4'{
   stage ('Checkout'){
      checkout scm
      
   }

      stage ('Build gradle'){
      sh "${gradle4}/bin/gradle clean jar"
   }
}

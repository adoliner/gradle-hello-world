node {'slave1'} {
 gradle4 = tool 'gradle4'
 stage ('chekcout'){
    checkout scm
 }
 stage ('build')
 {
     sh "${gradle4}/bin/gradle clean jar"
 }

 }

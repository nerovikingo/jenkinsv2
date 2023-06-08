pipeline {
   agent { node { label 'qa'} }

   stages {
       stage('primera_prueba') {
           steps {
             dir("/home/reguser/jenkinsv2/") {
	       sh 'pwd'
               sh 'touch alpha+$(date +"%Y%m%d%H%M")'
	     } 
	     }
       }        
           }
       }

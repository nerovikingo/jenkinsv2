pipeline {
   agent { node { label 'qa-v2'} }

   stages {
       stage('primera_prueba') {
           steps {
             dir("/var/www/qa/jenkinsv2/") {
	       sh 'pwd'
               sh 'touch alpha+$(date +"%Y%m%d%H%M")'
	     } 
	     }
       }        
           }
       }

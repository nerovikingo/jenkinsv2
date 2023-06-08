pipeline {
   agent { node { 
	   	label 'qa-v2'
	   	customWorkspace '/var/www/qa/jenkinsv2'
   } 
	 }

   stages {
       stage('primera_prueba') {
           steps {
               sh 'pwd'
               sh 'touch alpha+$(date +"%Y%m%d%H%M")'
	      }
       }        
           }
       }

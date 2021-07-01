stage('Code Checkout') { 
steps { 
checkout([ $class: 'GitSCM',
 branches: [[name: '*/master']],
 userRemoteConfigs: [[credentialsId: '8f78f1e6-e341-429d-b77e-86d25ec06159', url: 'https://github.com/spring-projects/spring-petclinic.git']]
 ])
 }
 }

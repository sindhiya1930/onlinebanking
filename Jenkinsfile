node {

   stage('Preparation') { //for display purposes
      git 'https://github.com/sunlove123/onlinebanking.git'
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
   }
   stage('Build') {
      // Run the maven build<appndid>

         sh "clean package -DskipTests=True"
     
   }
   stage('Results') {
         sh "clean"
   }
}

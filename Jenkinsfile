pipeline {
   agent any

   tools {
      // Install the Maven version configured as "M3" and add it to the path.
	  jdk 'JAVA'
      maven "Maven-3.3.9"
   }
   
   stages
   {
   stage('checkout') {
         steps {
            // Get some code from a GitHub repository
            git 'https://github.com/avinash-Gla/Game.git'
        }
        
        }
	}
}

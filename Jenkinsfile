pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo "Hello, Pipeline!"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          javac Main.java
          // Execute the compiled Java binary called HelloWorld. This requires JDK configuration from Jenkins
          java Main
        }
   }
   stage('Test') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying...'
     }
   }
  }
}

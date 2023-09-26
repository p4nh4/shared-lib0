@Library('lib-0') // Replace with the name of your global shared library

pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        echo "Building..."
        // Call a function from the global shared library
        myFunction()
      }
    }
    
    stage('Test') {
      steps {
        echo "Testing..."
        // Call a method from a class in the global shared library
        myClass.myMethod()
      }
    }
    
    stage('Deploy') {
      steps {
        echo "Deploying..."
        // Call another function from the global shared library
        myOtherFunction()
      }
    }
  }
}

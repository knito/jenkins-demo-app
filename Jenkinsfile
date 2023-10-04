@Library("shared-library") _
pipeline {
  agent { label "macos" }
  stages {
    stage("Example"){
      steps {
        helloWorld()
        // sh "echo Hello World"
      }
    }
  }
}
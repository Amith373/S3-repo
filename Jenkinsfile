pipeline {
  agent any
    stages {
      stage ("build with version") {
        steps {
          sh "java --version"
          sh "ls"
            }
          }
      stage ("deploy to s3") {
        steps {
         sh 'aws s3 cp * s3://amith-demo-website-03/'
         }
       }
    }
}

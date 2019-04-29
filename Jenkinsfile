pipeline {
     agent any
     stages {
          stage("build") {
               steps {
                    sh "./gradlew build"
               }
          }
          stage("start apps") {
               steps {
                    sh "./gradlew npm_start"
               }
          }
     }
}

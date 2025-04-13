pipeline {
  agent any
  tools {
    gradle 'Gradle-8.13'
  }
  stages {
    stage("run backend") {
      steps {
        echo 'Configuring gradle'
        sh './gradlew -v'
      }
    }

     stage("run frontend") {
      steps {
        echo 'Will configure frontend in future'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage("run backend") {
      steps {
        echo 'Configuring gradle'
        withGradle() {
          sh './gradlew -v'
        }
      }
    }

     stage("run frontend") {
      steps {
        echo 'Will configure frontend in future'
      }
    }
  }
}

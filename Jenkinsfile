pipeline {
  agent any
  stages {
    stage("configure backend") {
      steps {
        echo 'Configuring gradle'
        withGradle() {
          sh './gradlew -v'
        }
      }
    }

     stage("configure frontend") {
      steps {
        echo 'Will configure frontend in future'
      }
    }
  }
}

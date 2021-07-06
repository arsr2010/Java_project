pipeline {
    agent any
  /*  environment {
        POM_VERSION = readMavenPom().getVersion()
        BUILD_RELEASE_VERSION = readMavenPom().getVersion().replace("-SNAPSHOT", "")
        IS_SNAPSHOT = readMavenPom().getVersion().endsWith("-SNAPSHOT")
        GIT_TAG_COMMIT = sh(script: 'git describe --tags --always', returnStdout: true).trim()
    }
    */
    stages {
        stage('stage one') {
            steps {
                script {
                    echo "stage 1"
                }
                echo "tags_extra: ${tags_extra}"            }
        }
        stage('stage two') {
            steps {
                echo "stage two"
            }
        }
      stage('stage three'){
            steps {
                echo "stage 3"
            }
        }
    }
}

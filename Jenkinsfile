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
                sh    " git branch: 'development', credentialsId: '78ff28dc-af4a-4433-86b5-49dc2076c7f3', url: 'https://github.com/arsr2010/Java_project.git'"
                }
                           }
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

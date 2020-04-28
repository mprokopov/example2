pipeline {
  stages {
    stage('Build') {
      steps {
        sh 'tar czvf example2.tar.gz *.rb'
      }
    }
    stage('Publish') {
      steps {
        archiveArtifact 'example2.tar.gz'
      }
    }
}

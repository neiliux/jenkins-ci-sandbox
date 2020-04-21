pipeline {
  agent {
      dockerfile {
          filename 'Dockerfile'
          dir 'build'
          additionalBuildArgs  ''
          args ''
      }
  }
  stages {
      stage('Stage 1') {
          steps {
              echo 'Hello world!' 
          }
      }
  }
}


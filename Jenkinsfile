pipeline {
  agent {
      dockerfile {
          filename 'Dockerfile'
          dir 'build'
          label 'ci-sandbox'
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


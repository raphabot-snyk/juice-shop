pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        snykSecurity(failOnError: true, organisation: 'raphabot-snyk', snykInstallation: 'snyk-latest', additionalArguments: 'test', snykTokenId: 'raphabot-snyk-token')
      }
    }

  }
}
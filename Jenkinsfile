pipeline {
  agent any
  stages {
    stage('Open Source Scan') {
      steps {
        snykSecurity(snykInstallation: 'snyk-latest', organisation: 'raphabot-snyk', additionalArguments: 'test', snykTokenId: 'raphabot-snyk-token')
      }
    }

  }
}
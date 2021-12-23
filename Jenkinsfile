@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
	
 stage('ApiKeyValueMapDownload Command') {
	
	  apiKeyValueMapDownload script: this
  }
}

pipeline {
    agent any
	stages {
        stage('Build') {
            steps{
			    sh 'mvn package' 
                archiveArtifacts artifacts: '**/target/*.war', fingerprint: true 
			}
        }
    }
veracode applicationName: 'jenkins-pipeline', createProfile: true, criticality: 'VeryHigh', debug: true, fileNamePattern: '', replacementPattern: '', sandboxName: '', scanExcludesPattern: '', scanIncludesPattern: 
'', scanName: '', teams: '', timeout: 60, uploadExcludesPattern: '', uploadIncludesPattern: '**/**.war', useIDkey: true, vid: 'dd8a37f63ef2ecdbdf6e806195007d0f', vkey: 
'ef67607ffd6ffad6e62382862d681b4cdb48aba354b16d57329c34a3cc912b3f9528c9b3423e5caa350496b52e5873629ab67137745523d7a609b31f4feb5952', vpassword: '', vuser: ''


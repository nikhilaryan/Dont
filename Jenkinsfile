pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                   s3Upload(consoleLogLevel: 'INFO', dontWaitForConcurrentBuildCompletion: false, entries: [[bucket: 'aryabucketformeonly', excludedFile: 'Jenkinsfile', flatten: false, gzipFiles: false, keepForever: true, managedArtifacts: true, noUploadOnFailure: false, selectedRegion: 'us-gov-east-1', showDirectlyInBrowser: true, sourceFile: 'something.txt', storageClass: 'STANDARD', uploadFromSlave: false, useServerSideEncryption: false]], pluginFailureResultConstraint: 'FAILURE', profileName: '', userMetadata: [])
                 }
                 }
         }
}

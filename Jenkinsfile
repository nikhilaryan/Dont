pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                   s3Upload(consoleLogLevel: 'INFO', dontWaitForConcurrentBuildCompletion: false, entries: [[bucket: 'aryabucketformeonly', excludedFile: '', flatten: false, gzipFiles: false, keepForever: false, managedArtifacts: true, noUploadOnFailure: false, selectedRegion: 'us-east-1', showDirectlyInBrowser: false, sourceFile: 'something.txt', storageClass: 'STANDARD', uploadFromSlave: false, useServerSideEncryption: false]], pluginFailureResultConstraint: 'FAILURE', profileName: '', userMetadata: [])}
                 }
         }
}

@Library('piper-lib-os') _
node()
{     
    environment {
        PATH="/opt/sap/neo-sdk/tools:$PATH"      
   }
   stage('initial')
   {
   echo "PATH=$PATH"   
   fioriOnCloudPlatformPipeline script:this
   }
}

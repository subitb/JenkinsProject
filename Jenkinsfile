
node()
{     
    environment {
        PATH="/opt/sap/neo-sdk/tools:$PATH"      
   }
   stage('initial')
   {
   echo "PATH=$PATH"   
   @Library('piper-lib-os') _
   fioriOnCloudPlatformPipeline script:this
   }
}

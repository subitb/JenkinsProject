
pipeline()
{     
    environment {
        PATH="/opt/sap/neo-sdk/tools:$PATH"      
   }
   agent none
   stages{
   stage('initial')
   {
   steps
   {
   echo "PATH=$PATH"  
}   
   @Library('piper-lib-os') _
   fioriOnCloudPlatformPipeline script:this
   }
   }
}

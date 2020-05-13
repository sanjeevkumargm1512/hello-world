pipeline{
    agent any
    
    environment{
        PATH = "/opt/maven/bin:$PATH"
    }
     stages{
          stage('Git Clone'){
               steps{
                   git credentialsId: 'github', url: 'https://github.com/sanjeevkumargm/hello-world/'
               }
          }
          stage('Maven Build'){
               steps{
                   git credentialsId: 'github', url: 'https://github.com/sanjeevkumargm/hello-world/'
               }
         
     }
}

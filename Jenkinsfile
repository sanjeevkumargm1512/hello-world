pipeline{
    agent any
    
    environment{
        PATH = "/opt/maven/bin:$PATH"
    }
     stages{
          stage('Git Clone'){
               steps{
                   sh "rm -rf *"
                   git credentialsId: 'github', url: 'https://github.com/sanjeevkumargm/hello-world/'
               }
          }
          stage('Maven Build'){
               steps{
                   sh "mvn clean package"
               }
          }
     }
}

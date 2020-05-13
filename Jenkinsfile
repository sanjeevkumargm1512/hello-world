pipeline{
    agent any
     stages{
          stage('Git Clone'){
               steps{
                   git credentialsId: 'github', url: 'https://github.com/sanjeevkumargm/hello-world/'
               }
          }
     }
}

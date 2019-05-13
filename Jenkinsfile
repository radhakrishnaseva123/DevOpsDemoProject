def worksapce;
node
{
    stage ('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/radhakrishnaseva123/DevOpsDemoProject.git']]])
        workspace =pwd()
    }
    stage ('Static code Analysis')
    {
        echo "Static code Analysis"
    }
     stage('Build The Code')
     {
         echo "Build the code"
     }
     stage ('Unit Testing')
     {
         echo "Unit testing"
        
     }
    stage ('Devlivery the code')
    {
        echo "Devlivery the code"
    }
    
}

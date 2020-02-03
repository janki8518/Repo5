node('master')
{
    stage('ContinuousDownloadLoan') 
    {
        git 'https://github.com/intelliqittrainings/maven.git'
    }
    stage('ContinuousBuildLoan')
    {
        sh label: '', script: 'mvn package'
    }
 
    }
    
    
    
    
    
    
    
    
    
    
}

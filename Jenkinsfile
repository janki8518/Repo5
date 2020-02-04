node('master')
{
    stage('ContinuousDownload_master') 
    {
        git 'https://github.com/intelliqittrainings/maven.git'
    }
    stage('ContinuousBuild_master')
    {
        sh label: '', script: 'mvn package'
    }
    
    
    
    
    
    
    
    
    
    
}

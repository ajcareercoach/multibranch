node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'git clone https://github.com/ajcareercoach/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}

node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'git clone https://github.com/ajcareercoach/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}

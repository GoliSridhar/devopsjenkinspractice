node('master') 
{
    stage('Continuous Download of Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build of Master') 
	{
    sh label: '', script: 'mvn package'
	}
}

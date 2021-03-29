node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/ramreddyk1236/multibranching.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}

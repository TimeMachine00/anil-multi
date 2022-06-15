node('master') 
{
    stage('Continuous Download') 
	{
          git 'https://github.com/TimeMachine00/multibranchJenkin.git'
	}
	
stage('Continuousbuild_loans')
         {
          sh 'mvn package'
        }

    
}

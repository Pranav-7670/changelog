pipeline
{
  agent any
  stages
  {
     stage('build')
     {
       when
      {
        changeRequest ()
      }
      steps
      {
        echo "Hello world changing"
      }
     } 
  } 
}

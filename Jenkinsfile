pipeline
{
  agent any
  stages
  {
     stage('build')
     {
       when
      {
        changeRequest title: "when-pr"
      }
      steps
      {
        echo "Hello world changing"
      }
     } 
  } 
}

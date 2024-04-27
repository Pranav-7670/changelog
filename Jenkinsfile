pipeline
{
  agent any
  stages
  {
     stage('build')
     {
       when
      {
        changelog '.*some_text*.'
      }
      steps
      {
        echo "Hello world changing"
      }
     } 
  } 
}

pipeline
{
  agent any
  stages
  {
     stage('build')
     {
       when
        {
           changeset pattern: "*.js"
        }
      steps
      {
        echo "Hello world changing"
      }
     } 
  } 
}

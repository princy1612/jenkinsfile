

pipeline {
 agent any
     stages
      {
       stages('build')
       {
         git 'https://github.com/princy1612/jenkinsfile.sh'
      steps
        {
        echo "buliding the application .."
    }
    }
        stages('Testing')
       {
      steps
         {
    echo " testing the application ..."
   }
   }
        stages('Deploy')
     {
   steps
   {
      echo "deplying the application .."
    }
   }
  }
  }

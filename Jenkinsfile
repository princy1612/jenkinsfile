

pipeline {
 agent any
     stages
      {
       stage('build')
       {
         git 'https://github.com/princy1612/jenkinsfile.sh'
      steps
        {
        echo "buliding the application .."
    }
    }
        stage('Testing')
       {
      steps
         {
    echo " testing the application ..."
   }
   }
        stage('Deploy')
     {
   steps
   {
      echo "deplying the application .."
    }
   }
  }
  }

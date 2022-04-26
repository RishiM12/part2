pipeline { 
  agent any 
  stages { 
    stage('Testing') { 
      steps { 
        echo 'running Tests' 
        bat 'python course.py'
      } 
    } 
    stage('Build') { 
      steps { 
        echo 'Building jar files...'
      } 
    } 
  } 
}

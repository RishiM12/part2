pipeline { 
  agent any 
  stages { 
    stage('Testing') { 
      steps { 
        echo 'running Tests' 
        bat 'python courses.py'
      } 
    } 
    stage('Build') { 
      steps { 
        echo 'Building jar files...'
      } 
    } 
  } 
}

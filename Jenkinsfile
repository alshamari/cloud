pipeline {
    agent any
    stages{
        stage ('clone'){
        steps{
            checkout scm 
        }
    }
    stage ('bulid'){
        steps{

        sh "python -u /Users/alshamari/re/application/api.py" 
        }
    }
    
}
}


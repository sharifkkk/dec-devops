pipeline {
    agent any 
    parameters {
  choice choices: ['master', 'sharif', 'john'], description: 'enter your choice of branch', name: 'branch', trim: true
}

stages{
    stage('example'){
        steps {
            echo "${branch}, welcome to the world"
        }
    }
}
}

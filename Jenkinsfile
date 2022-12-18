pipeline {
    agent any 
    parameters {
  choice choices: 'master\nsharif\njohn', description: 'enter your choice of branch', name: 'branch'
}

stages{
    stage('example'){
        steps {
            echo "${branch}, welcome to the world"
        }
    }
}
}

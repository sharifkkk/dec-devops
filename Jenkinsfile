pipeline {
    agent any 
    parameters {
  string defaultValue: 'sharif', description: 'enter your name:', name: 'NAME', trim: true
}
stages{
    stage('example'){
        steps {
            echo "${NAME}, welcome to the world"
        }
    }
}
}

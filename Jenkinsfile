@Library('my-shared-library')_
pipeline {
agent any
stages {
stage('hello') {
steps {
    evenorodd(currentBuild.getNumber())
}
}
}
}

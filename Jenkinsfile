pipeline {
agent any
stages {
stage('stage 1') {
steps {
   catchError(buildResult: 'UNSTABLE', message: 'Even if the build fails, we continue on', stageResult: 'UNSTABLE'){
        sh 'exit 1'
}
}
}
stage('stage 2') {
steps {
      echo "welcome to jenkins ${WORKSPACE}"
}
}
}
}

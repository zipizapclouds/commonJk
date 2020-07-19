pipeline {
    //agent any 
    //agent { docker { image 'node:14-alpine' } }
    agent { docker { image 'alpine' } }
        stages {
            stage('Build') {
                steps {
                    sh 'echo "alive from common!"'
                }
            }
        }
}

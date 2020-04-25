pipeline {
    agent any
    stages {
        stage ("Build") {
            steps {
                sh 'echo "Hello World!!!"'
                sh '''
                     echo "Testing shell scripts to see what works"
                    ls -lah
                    '''
            }
        }
        stage('Lint HTML') {
            steps {
                sh 'tidy -q -e *.html'
              }
         }
    }
}

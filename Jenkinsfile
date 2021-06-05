pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World from PR 2'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}

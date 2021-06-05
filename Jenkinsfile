pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World from a PR with no label'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}

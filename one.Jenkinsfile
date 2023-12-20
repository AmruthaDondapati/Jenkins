pipeline {
    agent any
    environment { 
        URL = 'global.com'
    }
    stages {
        stage('Example1') {
            steps {
                echo 'one'
                echo "this refers to GLOBAL URL ${URL} "
            }
        }
        stage('Example2') {
            steps {
                echo 'two'
            }
        }
        stage('Example3') {
            steps {
                echo 'three'
            }
        }
    }
}
    
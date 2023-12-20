pipeline {
    agent any
    environment { 
        Link = "myyahoo.com"
    }
    stages {
        stage('Example1') {
            steps {
                echo 'one'
                echo "this refers to GLOBAL URL ${Link} "
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
    
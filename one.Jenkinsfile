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
        environment {
            Link = "myyahoolocal.com"
            }
            steps {
                echo 'two'
                echo "this refers to LOCAL URL ${Link} "
            }
        }
        stage('Example3') {
            steps {
                echo 'three'
            }
        }
    }
}
    
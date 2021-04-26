node {
    def branch_name = "aaaa"
}
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "${branch_name}"
                echo "Hello World"
            }
        }
    }
}



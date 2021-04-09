node {
    def branch_name = "${GIT_BRANCH}"
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

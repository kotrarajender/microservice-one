
pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                gitClone('main','git-cred','https://github.com/kotrarajender/microservice-one.git')
            }
        }
    }
}

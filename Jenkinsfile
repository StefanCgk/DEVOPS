pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
            }
        }
        stage('World') {
            input {
                message "Ok to proceed?"
                ok "Yes, we do."
            }
            steps {
                echo 'World'
            }
        }
    }
}

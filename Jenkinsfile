pipeline {
    agent none
    stages {
        stage('Build') {
            agent any
            options {
                skipDefaultCheckout() // Doesn't work if "agent any" is defined at pipeline level, it will work if options are set next to agent at pipeline level
            }
            steps {
                echo 'Hello'
            }
        }
    }
}

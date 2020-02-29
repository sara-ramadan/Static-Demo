pipeline {
    agent any
    stages {
        stage('Lint HTML') {
            when {
                branch 'master'
            }
            steps { 
                tidy -q -e *.html
                }
            }
        }
    }
}

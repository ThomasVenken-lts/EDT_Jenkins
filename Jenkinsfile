pipeline {
    agent none 
    stages {
        stage('Git pull & exec script') {
            steps {
                echo 'executing script'
				sh './hello_world.sh'
            }
        }
    }
}
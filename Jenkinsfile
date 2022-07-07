pipeline {
    agent none 
    stages {
        stage('Git pull & exec script') {
            steps {
                echo 'executing script'
				./hello_world.sh
            }
        }
    }
}
pipeline {
    agent none 
    stages {
        stage('Git pull & exec script') {
		agent none
            steps {
                echo 'executing script'
				sh './hello_world.sh'
            }
        }
    }
}
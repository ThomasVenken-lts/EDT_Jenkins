pipeline {
    agent any 
    stages {
        stage('Git pull & exec script') {
            steps {
                echo 'executing script'
				sh 'chmod +x hello_world.sh'
				sh './hello_world.sh'
            }
        }
    }
}
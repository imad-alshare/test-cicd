pipeline {
    agent any
    tools { 
        maven 'maven 3.6.3' 
        jdk 'jdk11' 
    }
    stages {
        stage ('Initialize') {
            steps {
                
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
    }
}

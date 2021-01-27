pipeline {

    agent any //where to execute

    stages { //where the work happens

        stage("build") {

            steps {
                //script that executes the command on jenkin server/agent
                echo 'building the application'
            }
        }
        stage("test") {

            steps {
                echo 'testing the application'
            }
        }
        stage("deploy") {

            steps {
                echo 'deploying the application'
            }
        }
    }
}


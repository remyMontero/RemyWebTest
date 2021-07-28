//toplevel
pipeline{
    //where to execute
    agent any
    //where all of the work happens
    stages{
        stage ("build"){
            steps{
                echo 'Jenkins building the application after changes...'
            }
        }
        stage ("test"){
            steps{
                echo 'Jenkins testing the application'
            }
        }
        stage ("deploy"){
            steps{
                echo 'Jenkins deploying the application'
            }
        }
    }
}

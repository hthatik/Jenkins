pipeline {

    agent any
    
    stages {
    
        stage("build") {
        
            steps {
                echo 'building the application...'
            }
        }
        
        stage("test") {
        
            steps {
                echo 'testing the application...'
            }
        }
        
        stage("deploy") {
        
            steps {
                echo 'deplying the application...'
            }
        }
        stage("deploy2") {
        
            steps {
                echo 'deplying the application2...'
            }
        }
    }   
    post{
        Success{
            echo 'deplying the application Success..'
        }
    }
}

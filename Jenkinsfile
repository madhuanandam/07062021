pipeline{
    agent any
    environment{
        NEW_VERSION = '1.3.0'
        SERVER_CREDENTIALS = credentials('server_credentials')
    }
    stages{
        stage("build"){
            steps{
                echo 'building app'
                echo "upgraded to '${New_Version}'"
            }
        }
        
    
        stage("test"){
            steps{
             echo 'testng app'
            }
        }
    
        
    
        stage("prod"){
            steps{
                echo 'prod'
                echo "credentials '${SERVER_CREDENTIALS}'"
            }
        }
    }
}

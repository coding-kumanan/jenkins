pipeline{
    agent any
    environment{
        GLOBEL = "globel-env"
    }
    stages{
        stage(stage1){
            steps{
                sh "echo Hi from stage1"
            }
            steps{
                sh "echo ${GLOBEL}"
            }
        }
    }
}
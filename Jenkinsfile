pipeline{
    agent any
    stages{
        stage("build"){
            when{
                changeset glob:"*.js"
            }
            steps{
                echo "Hello World change set"
            }
        }
    }
}
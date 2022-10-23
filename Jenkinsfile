pipeline
{
    agent any
        stages{
            stage('checkout GIT'){
                steps{
                    echo 'pulling...';
                    git branch : 'master',
                    url :'https://github.com/rafed-99/rafed-test-devops.git'
                }
            }
        }

}
pipeline {
    agent any 
        stages{
            stage('Build') {
                steps{
                    sh '''
                    a=4 
                    b=10 
                    c=$((a+b))
                    echo "Print the value of c is $c"
                    '''
                }
            }

            stage ('Testing') {
                steps{
                    echo "Testing its all good"
                }
            }

            stage ('Deploy') {
                steps{
                    echo "Pipeline addition successful"
                }
            }

        }
    
}
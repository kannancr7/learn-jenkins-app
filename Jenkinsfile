pipeline{
    agent any
    stages{
        stage('build'){
            steps{
            sh '''
            ls -la
            npm -v
            node -v
            npm ci
            npm run build
            ls -la

            '''
            }
        }
    
       
    }
}
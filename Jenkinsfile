pipeline{
    agent {
        label 'Slave1-BuildServer'
    }

    stages{
        stage ('git-clone'){
            steps{
                git branch: 'feature1', url: 'https://github.com/MithunEdappulath/projCert.git'
            }
        }
    }
}
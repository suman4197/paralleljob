pipeline { 
    agent any 
        stages {
            stage ('Build') { 
                steps {
                    git branch: 'main', url: 'https://github.com/suman4197/paralleljob.git'
                    sh 'mvn clean install'
                    echo "build is success"
                    }
                }
           }
     }

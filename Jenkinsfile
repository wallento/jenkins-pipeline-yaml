pipeline {
    agent {
        label 'librecores-ci-modules'
    }
    

    stages {
       stage("Test") {
           steps {
             def username = 'Jenkins'
             echo 'Hello Mr. ${username}'
             def datas = readYaml file: '.librecores-ci.yaml'
             echo 'Hello World'
           }
       }
    }
}

pipeline {
    agent {
        label 'librecores-ci-modules'
    }
    
    def datas = readYaml file: '.librecores-ci.yaml'

    stages {
       stage("Test") {
           steps {
             echo 'Hello World'
           }
       }
    }
}

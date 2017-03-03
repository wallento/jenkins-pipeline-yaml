pipeline {
    agent {
        label 'librecores-ci-modules'
    }
    stages {
       stage("Test") {
           steps {
             def datas = readYaml file: '.librecores-ci.yaml'
             echo 'Hello World'
           }
       }
    }
}

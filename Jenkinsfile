#!groovy

pipeline {
    agent any
    options {
        buildDiscarder(logRotator([
            daysToKeeStr: '7',
            numToKeepStr: '10'
        ]))
    }
    stages {
        stages ('prueba) {
            steps {
                echo "FUNCIONA"
            }
        }
    }
}    
#!groovy

pipeline {
    agent any
    options {
        buildDiscarder(logRotator([
            daysToKeeStr: '7',
            numToKeepStr: '10'
        ]))
    }
    stage {
        stage ('prueba') {
            steps {
                echo "FUNCIONA"
            }
        }
    }
}    

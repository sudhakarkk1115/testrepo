pipeline{
    agent any
    parameters {
      choice choices: ['dev', 'sit', 'pt', 'prod'], description: 'select environment', name: 'ENV'
    }
    environment {
      JAVA_HOME = "/usr/bin/java8"
    }

    stages{
        stage("Welcome to Jenkins") {
            steps {
                script{
                    // Printing default variables
                    println "BUILD_NUMBER is ${BUILD_NUMBER}" 
                    println "WORKSPACE is ${WORKSPACE}"

                    // Printing value of parameters
                    println "Selected environment is ${params.ENV}"  

                    // Printing environment variables
                    println "my Java home path is ${env.JAVA_HOME}"     
                }
            }
        }
    }
}

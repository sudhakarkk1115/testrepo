def myfn(a,b){
    println "Welcome to functions"
    println "My a value is ${a} & my b value is ${b}"
}


pipeline {
    agent any
    stages {
        stage("Welcome to Jenkins"){
            steps {
                script {
                    // calling a function
                    myfn(200,100)                    
                }
            }

        }
    }
}

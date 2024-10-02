def myfn(a=2000,b=3000){
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
                    myfn()
                    myfn(200,100)
                    myfn(100)                    
                }
            }

        }
    }
}

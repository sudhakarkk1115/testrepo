pipeline {
    agent any
    stages {
        stage("Welcome to Jenkins"){
            steps {
                script {
                    for(i=1;i<=10;i++){
                        println "my i value is ${i}"
                    }

                    list1=[10,20,30,40]
                    for (i in list1) {
                        println "my i value is ${i}"
                    }                    
                }
            }

        }
    }
}

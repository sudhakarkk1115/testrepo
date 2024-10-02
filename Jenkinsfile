pipeline {
    agent any
    stages {
        stage("Welcome to Jenkins"){
            steps {
                script {
                    // reading lines from file
                    File myfile = new File("/tmp/test.txt")
                    lines = myfile.readLines()
                    // printing each line
                    println lines
                    for (line in lines)
                    // printing all lines
                    println line


                    
                }
            }

        }
    }
}

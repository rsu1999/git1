pipeline {

  agent any
  environment {
    HTML = "4.4"
  }
  stages {
     stage('Build docker image') {
          // this stage also builds and tests the Java project using Maven
          steps {
            fileOperations([fileRenameOperation(source: 'folder/test.html', destination:"folder/test-${HTML}.html")])
            
          }
      }
                            }
                            }
    

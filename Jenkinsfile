pipelineJob('demo-two') {
  definition {   //Adds a workflow definition
    cps {
      script('''
       pipeline {
            agent any
                stages {
                    stage('Stage 1:Build') {
                        steps {
                            echo 'Ready to build'
                        }
                    }
                    stage('Stage 2:Deploy') {
                        steps {
                            echo 'Ready for deployment'
                        }
                    }
                }
            }
          ''')
         }
      }
 }

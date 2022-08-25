pipeline  {
  agent any
  stages  {
    stage("stage1")  {
      steps  {
         script  {
            bat  "mvn clean install"
            echo "Stage 1 Completed"
            }
          }
        }
     stage("stage2")  {
      steps  {
         script  {
            echo "mvn clean install completed"
            sleep 10
            echo "Stage 2 Completed"
            }
          }
        }
     }
 }

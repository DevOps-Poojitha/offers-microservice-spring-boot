pipeline  {
  agent any
  stages  {
    stage("stage1")  {
      steps  {
         script  {
            bat  "mvn clean install"
            }
          }
        }
     stage("stage2")  {
      steps  {
         script  {
            echo "mvn clean install completed"
            sleep 10
            }
          }
        }
     }
 }

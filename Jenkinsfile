pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo trigger') {
      steps {
        echo 'hello from the trigger'
      }
    }

  }
}

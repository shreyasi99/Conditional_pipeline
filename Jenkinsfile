pipeline {
    agent any 
  stages {
    stage ('ONE choice') {
      when {
                expression { param.choice == 'ONE'}
            }
            steps {
                echo "Hello, Choice ONE!"
            }
    }
    stage ('TWO choice') {
      when {
                expression { param.choice == 'TWO'}
            }
            steps {
                echo "Hello, Choice TWO!"
            }
    }
  }
}

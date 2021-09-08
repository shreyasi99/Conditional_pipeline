pipeline {
    agent any 
  stages {
    stage ('ONE choice') {
      when {
                expression { choice == 'ONE'}
            }
            steps {
                echo "Hello, Choice ONE!"
            }
    }
    stage ('TWO choice') {
      when {
                expression { choice == 'TWO'}
            }
            steps {
                echo "Hello, Choice TWO!"
            }
    }
  }
}

pipeline{
	agent any
	stages{
		stage('build'){
			steps{
				bat 'echo "building" '
				bat 'javac hello.java'
				bat 'java Hello'
			}
		}
	}
}

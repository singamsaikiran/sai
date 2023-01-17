node {
    stage('git clone') {
	git credentialId: 'singamgits', url: 'https://github.com/singamsaikiran/sai.git'
	
	}
	stage('maven clean') {
	bat'''mvn clean'''
	
	}
	stage('maven validate') {
	bat'''mvn validate'''
	
	}
	stage('maven compile') {
	bat'''mvn compile'''
	
	}
	stage('maven test') {
	bat'''mvn test'''
	
	}
	stage('maven package') {
	bat'''mvn package'''
	
	}
	
}	
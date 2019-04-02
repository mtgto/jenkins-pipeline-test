pipeline {
	agent any
		stages {
			stage('test') {
				steps {
					echo "GIT_COMMIT = ${GIT_COMMIT}"
					echo "HEAD: "
					sh "git rev-parse HEAD^{commit}"
				}
			}
		}
}

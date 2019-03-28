pipeline {
	agent any
		stages {
			stage('test') {
				steps {
					echo "${GIT_COMMIT}"
					sh "cat .git/FETCH_HEAD"
				}
			}
		}
}

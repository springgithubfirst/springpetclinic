node {

	stage('SCM')
	{
	     git branch: 'test', changelog: false, url: 'https://github.com/springgithubfirst/springpetclinic.git'
	}

	stage('BUILD')
	{
	sh 'mvn package'
	}

}



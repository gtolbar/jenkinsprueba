pipeline {
    agent any
	
    options{
        timeout(time: 2,unit: 'MINUTES')
	}
	
    stages {
        stage('mostrar contenido') {
            steps {
                cat README.md
            }
        }
        stage('Hola mundo') {
            steps {
                echo 'Testing..'
            }
        }

    }
}

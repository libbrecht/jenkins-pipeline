pipeline { 
	agent any 
	stages {
		stage('build'){
			steps{
				echo 'etape de build'
				sh 'python --version'
			}
		}
		stage('test'){ 
			steps{
				echo 'etape de test'
			}
		}
		stage('deploy'){ 
			steps{
				echo 'etape de deploiement' 
			} 
		}   
	}
}  

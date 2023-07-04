pipeline {
    agent any

    stages {
        
        stage ('fazendo ssh para o servidor do kubernetes e executando deploy no Kubernetes') {
                    steps {
                        script {
                                sh 'ssh docker@192.168.25.239 | kubectl apply -f /home/docker/teste_deployment.yaml'

                        }
                    }

        }
    }
}
pipeline {
    agent any
	triggers { cron('* * * * *') }
    options { timeout(time: 5) }
    parameters {
        booleanParam(name: "MOSTRAR_STEP", defaultValue: true,
        description: "¿QUIERES EJECUTAR EL CÓDIGO?")
    }
    environment { NAME = "RAUL" }
    stages {
        stage("Primer_Stage") {
            when { expression { params.MOSTRAR_STEP } }
            steps {
                script {
                    echo "Step 1. Hola ${NAME}. SE EJECUTA EL CÓDIGO DE STEP 1"
                }
            }
        }
        stage("Segundo_Stage") {
            steps {
                script {
                    echo "Step 2."
                    echo "Step 3."
                }
            }
        }
    }
    post {
        always {
            echo "Fin del pipeline"
        }
    }
}

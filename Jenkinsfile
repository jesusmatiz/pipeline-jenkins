node {
   
    stage('Clone recursos') {
        git url: 'https://github.com/jfrogdev/project-examples.git'
    }

    stage('Construyendo proyecto') {
        echo "Construyendo proyecto"
    }

    stage('Generando pruebas') {
        echo "Probando codigo"
    }

    stage('SonarQube') {
        echo "Probando con SonarQube"
    }

    stage('Despliegue') {
        echo "Desplegando proyecto"
    }
}
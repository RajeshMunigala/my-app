node {
    
    stage('scm-checkout'){
        
        echo "Git checkout"
        git "https://github.com/javahometech/my-app"
    }
    
    stage('compile-build'){
        
        def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn clean package"
    }
    
}

node {
    
     tools {
    maven 'maven3'
  }
    
    stage('checkout'){
        
        echo "Git checkout"
        git "https://github.com/javahometech/my-app"
    }
    
    stage('building'){
        
        sh "mvn clean package"
    }
    
}

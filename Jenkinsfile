node {
    
    stage('checkout'){
        
        echo "Git checkout"
        git "https://github.com/javahometech/my-app"
    }
    
    stage('building'){
        
        mvn clean package
    }
    
}

node {
    
    stage('checkout'){
        
        echo "Git checkout"
        git "https://github.com/javahometech/my-app"
    }
    
    state('building'){
        
        mvn clean package
    }
    
}

node{
    stage("Shubam first pipeline"){
        echo "shubam first pipeline"
    }
    if(params.Skip_The_Stage == true){
             stage("Shubam second pipeline"){
                echo "shubam second pipeline"
            }
    }
     stage("Shubam third pipeline"){
        echo "shubam third pipeline"
    }
}
node {

    
    
stage('scm') {
    
   

 git 'https://github.com/manikantadevopss/game-of-life.git'


}
     
 stage('build&package') {

         
         
sh 'mvn package'


}
 
   
 stage('result') {
   
           
 
 archive 'gameoflife-web/target/gameoflife.war'

           
 junit 'gameoflife-web/target/surefire-reports/*.xml'

}

}

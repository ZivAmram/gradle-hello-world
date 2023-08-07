node a{
  
  stage 'Checkout'
    git url: 'https://github.com/ZivAmram/gradle-hello-world.git'
    
  def gradleHome = tool 'gradle4'

   // Mark the code build 'stage'....
  stage 'Build'
   // Run the maven build
  sh "${gradleHome}/bin/mvn clean install"
}
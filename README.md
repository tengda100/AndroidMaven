This Project is an Android Maven Skeleton to get anyone started: (Assuming you have Eclipse or ADT Studio setup)

1.Install Maven : if you have Homebrew installed : brew install maven
   Useful Links :
   	- http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
   	- http://www.mkyong.com/maven/install-maven-on-mac-osx/
   	- http://www.mkyong.com/maven/how-to-install-maven-in-windows/
   	 
2.Install m2e-android
  Useful Links : 
    - http://rgladwell.github.io/m2e-android/

3.Install Eclipse Marketplace on ADT: 
   1. Help->Install New Software...
   2. Point to Eclipse Indigo Site, If not available add the site "Indigo - http://download.eclipse.org/releases/indigo"
   3. Work with the above site
   4. Look at "General Purpose Tools"->Marketplace Client
After installing, restart Eclipse and you can find Marketplace in "Help->Eclipse Marketplace..."
     

Getting Started Maven-Android-Plugin: 
https://code.google.com/p/maven-android-plugin/wiki/GettingStarted

Maven : The Complete Reference (Android Development with Maven)
http://books.sonatype.com/mvnref-book/reference/android-dev.html   
   
Running this Project: 
To build, deploy and run the app on all attached devices/emulators : mvn clean install android:deploy android:run



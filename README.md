# Concrete Solutions DEV Workstation

This repository will hold scripts that will help you initialize a development environment for Android with Maven and Git using Eclipse.  


### Environment Bootstrap Targets

In order to have a proper Android development environment you will need:

* Oracle Java 7  
* Maven 3.+  
* Git  
* Android SDK  
* Eclipse  
* Eclipse Plugins (m2e-android, m2e-apt)  

Other than that the environment will depend on the following variables and executables in your path:

* JAVA_HOME  
* MAVEN_HOME  
* ANDROID_HOME
* mvn  
* adb, android, zipalign, etc  

This repository is intended to be maintained in order to be aligned with latest releases of Android. In order to remain compatible in between releases, some fixes will be provided. These currently include:

* Symbolic link of latest zipalign into its old directory  

Please post issues or comments as we tag along!

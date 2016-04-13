# SSOApp

Identity Proxy Application Repo for the Mobile Single Sign on Solution

This application was developed based on the IDP-Proxy-App in the [SDK] (https://github.com/Brian-Kaplan/WSO2-API-Manager/tree/master/android-idp-sdk-1.1.0/IDP-Proxy-App)

# Documentation

 - Much of the implementation is based on an [article](http://wso2.com/library/articles/2014/07/sso-for-native-mobile-applications-with-wso2-identity-server/) released by Gayan Gunawardana
 
 Installation
  
    - Simply clone the repo and open it in Android Studio
    - This applciation was installed and tested on a Nexus 5 Emulator Target API 22
    - Click the settings on top right and set the hostname to the ip of your server and the port to 9443
    
    - The SDK does not need to be installed with this application
    - If the Client ID and Client Secret are changed within the Servers Service Providers they must be changed in the OAuthConstants class

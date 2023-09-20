# Andriod-Huawei-Bluetooth-Based-Chat-App

This chat application uses React Native HMS Nearby Service Plugin.

# Note
You need 2 HMSCore APK installed phones to test this app. This application is tested on Huawei Y9 Prime and Huawei Y6.

# How to Run ❓
Clone the code or download the zip file and then install the dependencies using command below.

    npm i 
    
Put your agconnect-services.json and keystore_file.jks under android > app directory.

Then fill the android > app > build.gradle file as given below.

     defaultConfig {
           applicationId "<package_name>"  // your package name in agconnect-services.json
            ...
             }
    signingConfigs {
       config {
        storeFile file('<keystore_file>.jks') // your keystore filename
        storePassword '<keystore_password>'   // keystore password
        keyAlias '<key_alias>'                // key alias
        keyPassword '<key_password>'          // key password
        ...
        }
       ...
       }

# Run the application

    npx react-native run-android

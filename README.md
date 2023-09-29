
![hms-react-native-plugin](https://github.com/Shrekpepsi/Near-By-Chat/assets/107950320/2c62705e-d8f5-475e-8645-1434c7d6ded6)

# Andriod-Huawei-Bluetooth-Based-Chat-App 

This chat application uses React Native HMS Nearby Service Plugin.

# Note
You need 2 HMSCore APK installed phones to test this app. This application is tested on Huawei Y9 Prime and Huawei Y6.

# How to Run❓
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


# Getting Started
Note: Make sure you have completed the React Native - Environment Setup instructions till "Creating a new application" step, before proceeding.

# Step 1: Start the Metro Server
First, you will need to start Metro, the JavaScript bundler that ships with React Native.

To start Metro, run the following command from the root of your React Native project:

# using npm
npm start

# OR using Yarn
yarn start
Step 2: Start your Application
Let Metro Bundler run in its own terminal. Open a new terminal from the root of your React Native project. Run the following command to start your Android or iOS app:

For Android
# using npm
npm run android

# OR using Yarn
yarn android
For iOS
# using npm
npm run ios

# OR using Yarn
yarn ios

If everything is set up correctly, you should see your new app running in your Android Emulator or iOS Simulator shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

Now what?
If you want to add this new React Native code to an existing application, check out the https://reactnative.dev/docs/integration-with-existing-apps guide.

If you're curious to learn more about React Native, check out the Introduction to React Native.
Troubleshooting
If you can't get this to work, see the Troubleshooting page.

# Learn More
To learn more about React Native, take a look at the following resources:

React Native Website - learn more about React Native.
Getting Started - an overview of React Native and how setup your environment.
Learn the Basics - a guided tour of the React Native basics.
Blog - read the latest official React Native Blog posts.
@facebook/react-native - the Open Source; GitHub repository for React Native.

## Screenshots

Phone 1 Broadcaster           |  Phone 2 Scanner
:-------------------------:|:-------------------------:
![InitialScreen](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/1a4034d1-02a2-4133-a3c1-fc5cebf6a2d6) | ![InitialScreen (1)](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/49ada43c-bf03-47f8-a2f2-4022d827780e)
![ScanningBroadcasting](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/a413abe4-6592-438c-b9dd-6e7eece91bdc) | ![ScanningBroadcasting (1)](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/557b89f7-a75f-4b1e-9296-6d1857d69104)
![BroadcastAuth](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/0753b848-c15e-40d3-81a6-e5956ae5a5b2) | ![ScanResult](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/2f072f17-d81d-4178-944b-546f4209e803)
| ![ScanAuth](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/1e1e1cbf-5c8e-49f9-8776-e2076092e381)
![ChatBroadcast](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/94022dce-9fcd-47ce-95ea-2b08db983613) |  ![ChatScan](https://github.com/Shrekpepsi/Andriod-Huawei-Bluetooth-Based-Chat-App/assets/107950320/7173538a-fd40-4a04-b283-db10d7c53a8a)











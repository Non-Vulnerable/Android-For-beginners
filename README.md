# Android-For-beginners
Android Penetration Testing
Android Pen-Testing: An Introduction for beginners

My first blog🤖

Hi hackers, i hope you doing well in hacking.

In this blog we are discussing about the introduction of the Android Penetration testing, In details parts for in depth of Same subject will be releasing soon.

Architecture of APK files.


For the beginners i would suggest to understand the basic understanding of android.

Linux based system(Open source)
A file with the APK file extension is a package file used to distribute apps on Google’s Android operating system.
An APK file is a ZIP archive, which can be extracted and readable via normal zip extraction(change .apk to .zip)
classes.dex: The classes compiled in the dex file format executed by Android Runtime (or by Dalvik virtual machine used in Android 4.4 KitKat).
Mostly all codes are visible while extracting the application
Programming languages: Java, Kotlin, C++, C#, Python, HTML, CSS, JavaScript, Dart, Corona
Setup required: One android phone rooted or any android emulator (Genymotion recommended), Linux or window machine, USB cable with respect to device, Burp suite pro or community.

Now begin with the pen testing methodology.

In Android pentesting there are two type of testing

Static analysis , Dynamic analysis

Static analysis - Static analysis is a method of debugging that is done by automatically examining the source code without having to execute the program
## Reviewing apk files, codes of the apk like we required only apk file for static (Not need to install and run the application)

Tools used for static analysis

Mobsf: Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.

apktool: A tool for reverse engineering 3rd party, closed, binary Android apps. It can decode resources to nearly original form and rebuild them after making some modifications; it makes possible to debug smali code step by step. Also it makes working with an app easier because of project-like file structure and automation of some repetitive tasks like building apk.

adb: Android Debug Bridge (adb) is a versatile command-line tool that lets you communicate with a device. The adb command facilitates a variety of device actions, such as installing and debugging apps. adb provides access to a Unix shell that you can use to run a variety of commands on a device. It is a client-server program that includes three components

JD-GUI : JD-GUI is a standalone graphical utility that displays Java source codes of “.class” files. You can browse the reconstructed source code with the JD-GUI for instant access to methods and fields.

JADX: Command line and GUI tools for producing Java source code from Android Dex and Apk files

Jarsigner: jarsigner adds a digital signature to the specified jarfile, or, if the -verify option is specified, it verifies the digital signature or signatures already attached to the JAR file. The specified signer is a case-insensitive nickname or alias for the entity whose signature is to be used. The specified signer name is used to look up the private key that generates the signature.

Apkeditor: This is the very best application to edit your APK files easily. With this app, you can explore the contents of an APK file, edit, save as well as change background images.

dex2jar: Used for convert .dex file into human readable format .jar files.

2. Dynamic analysis -Dynamic analysis is the process of testing and evaluating a program — while software is running

## Checking application functionalities and request with running application like logs review, traffic intercept(Need to install and run the application)

Tools used for static analysis

Burp Suite: Most of the guys knows about this popular tools but for newones i would like to tell you in short that this tools used to intercept the traffic based on proxy.

Drozer: drozer is a good tool for simulating a rogue application. A penetration tester does not have to develop an app with custom code to interface with a specific content provider. Instead, drozer can be used with little to no programming experience required to show the impact of letting certain components be exported on a device.

Logcat: Logcat is a command-line tool that dumps a log of system messages including messages that you have written from your app with the Log class. adb logcat supports additional filters that can reduce the amount of logs shown from logd. See the section about filtering log output for more details.(Android Debug Bridge (adb) is a versatile command-line tool that lets you communicate with a device used to attached and communicate device with cable)

Important test case:

Rooted device : Rooting is the process of unlocking or jailbreaking a device, such as a smartphone or tablet. It most commonly refers to android devices. A rooted device gives the user much more freedom to customize the device and achieve more administrative control.

SSL pinning : SSL pinning is a technique that helps to prevent MITM attacks by hardcoding the SSL/TLS certificate’s public key into the app or device.

Magisk: Magisk is an app which helps users to root their phone. With the help of Magisk you can run banking apps and also pass SafetyNet tests.

Objection: objection is a runtime mobile exploration toolkit, powered by Frida. It was built with the aim of helping assess mobile applications and their security posture without the need for a jailbroken or rooted mobile device.

frida: Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers. Learn more at frida.re.

For the initial stage this understanding will be very helpfull for you next in details parts are publishing soon for actual practical android pen testing.

For practice i would like to suggest to use mobsf automate scanner to analyze the apk files, for test application use DIVA.

I hope you guys has learned something from this blog, please hit like and share this blogs with your friends and follow for more android and iOS blogs. write comments if you have any query.

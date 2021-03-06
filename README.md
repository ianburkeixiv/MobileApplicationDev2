# 3rd Year Module Mobile Applications Development 2
# Introduction
This repository is for my UWP project for the module Mobile Application 2 in the course Computing and Software Development studied at Galway Mayo Institute of Technology (GMIT). Lecturer of the module is Damien Costello.

# UWP (Universal Windows Platform) Soundboard
For my project, I have decided to make a soundboard for my Windows application. The soundboard will consist of sounds from various characters based from a famous Irish television comedy called Father Ted. The user can navigate between characters and choose a sound to play. The user simply can click/tap a button to play a sound. 

### Windows Store Link
https://www.microsoft.com/en-us/store/p/father-ted-soundboard/9mzq2mmw07gw

# System Requirements
- Windows 10 Operating System
- Windows 10 Mobile
- Integrated Mouse
- Integrated Touch

# Architecture
### IDE
To develop the mobile app, I used Microsoft's [Visual Studio 2015](https://www.visualstudio.com/downloads/) as an IDE (integrated development environment). The application is a [UWP](https://docs.microsoft.com/en-us/windows/uwp/get-started/universal-application-platform-guide) (Universal Windows Platform) which was first introduced in Windows 10. The purpose of this software platform is to help develop universal apps that run on both Windows 10 and Windows 10 Mobile without the need to be re-written for each. 

### C# and XAML
[C#](https://msdn.microsoft.com/en-us/library/kx37x362.aspx) (pronounced C Sharo) is a hybrid of C and C++, it is a Microsoft programming language. C# is an object-oriented programming language used with XAML-based Web services on the .NET platform and designed for improving productivity in the development of Web Applications.

[XAML](https://msdn.microsoft.com/en-us/library/ms752059(v=vs.110).aspx) (Extensible Application Markup Language) is an XML-based markup language developed by Microsoft. It it tpically used to create an application's user interface. It's basically behind the visual presentation of an application just like HTML is the language behind the visual presentation of a Web Page.

Both C# and XAML interact with each other to create a Web application. Both are binding.


### Local Storage
The Assets folder in the UWP acts as the local storage. It is used to store the sounds and logos used in the soundboard app.

# Design
The app is very basic. I used pivots to navigate to different characters and sounds. Pivots are the same as tabs. To play the sounds, I used buttons. When the user clicks/taps a button, an event handler occurs where it calls the media element which plays the particular sound. The media element is used to get the source of the sound file. Once the media element is binded with the button click event handler. A play() method is called to play the sound. More on the Media Element at: https://msdn.microsoft.com/en-us/library/windows/apps/mt187272.aspx

# How to run
1. Download the above FT_Soundboard folder.
2. Open Visual Studio 2015 and create a windows universal blank app project
3. Paste in mainPage.xaml.c and mainPage.xaml.
4. Add the assets folder containing the sounds.
5. Run on local machine.

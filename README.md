# A Little Exploration on Android Studio
As an Android developer, it is imperative for me to learn the tools that I'm going to use, in this case, the official integrated development environment (IDE), Android Studio. For you guys that have been using JetBrains' IDE platform, you may be feeling really familiar with Android Studio, and that is really justified, because Android Studio was built on JetBrains' IDE for Java development, IntelliJ IDEA. Android Studio, as ubiquitous of an operating system it is, can be downloaded on Windows, macOS, and Linux-based OS. Currently, Android Studio is on version 4.1, the version of which was just released on 12 October 2020. Android Studio supports several languages, not just Java, such as C++, Go, Kotlin (Android Studio 3.0++). Some of the features provided by the latest Android Studio are: Gradle-based build support, layout editor that can be used to drag-and-drop UI layout components, support for building Android Wear apps, built-in support to Google Cloud Platform, integration with Firebase Cloud, and lastly, Android Virtual Device emulator to run and debug apps in an Android-emulated environment.

In my opinion, there are several strengths and weaknesses for Android Studio.
First, the strength of Android Studio are:
+ The debug mode is really helpful in assisting you to find the errors in your code
+ It supports multiple languages
+ Seamless integration to Git
+ Integrated emulator for easy debugging and planning
+ It is 100% open source and there is a large number of communities able to assist you should you get stuck
+ Coding novices can get to work fairly easily with how simple the Android Studio's UI is

Second, from my experience, the weakness of Android Studio are:
- It is super slow to open from a cold start
- First code build may take minutes, sometimes up to tens of minutes. But after that, it will be much faster. This is caused by the Android Studio needing time to kickstart the emulation of Android OS
- Consequently, Android Studio also demands lot of memory and processing power in order to work flawlessly
- And whenever there's an update, be prepared to take some time off of your coding time, since the updates are usually unable to be put in the background and there can be quite a lot to update.

Of course, one of the reason I explored Android Studio is because of my experience in using it. I have been involved in several startups that forced me to be able to use Android Studio. **One of my projects can be seen [here](https://github.com/RiajuuAlbert/StockAnalysisApp)**. This app is not the most recent version, as it is currently in development and is a company secret. This app basically is a stock screener, where you check if a company's stock is preferrable or not based on the technical indicators available. First, you put in the name of the company (in ticker code, a four lettered code for publicly listed companies in Indonesia), and then you check whether the technical indicators are supporting you to buy or sell the stock. One of the planned development to said app is by implementing machine learning model to help in giving a solid and accurate recommendation to the user by taking in historical price data of the stock, and combining with the technical indicators.

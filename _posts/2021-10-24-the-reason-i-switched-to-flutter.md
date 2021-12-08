---
title: The Reason I Switched To Flutter
date: 2021-08-17 12:00:00
categories: [Flutter]
tags: [flutter, opinion]
image:
  src: https://cdn.jsdelivr.net/gh/sapatekno/sapatekno-assets/images/flutter-logo.png
  width: 500
  height: 250
  alt: Logo Flutter
---

I have been an ***Android Developer*** for more than 3 years, the first year I used Kotlin as a programming language to create android applications, but then when my job required me to use Flutter Framework, I finally switched to using Flutter Framework until now, it's been 2 years at least 5 the project I work on using Flutter, I like it, the existence of the Flutter Framework is very helpful in making android applications easier than when I use Kotlin, at least there are several points that are the reason I really like this Flutter Framework, including:
 
### **Hot Reload**

The problem when I build an Android app using Kotlin is that when I make small changes I have to wait for the recompile process to show the changes I want on the device, it does take some time to wait but I think it's a bit annoying and time consuming, with Flutter the issue is resolved with the feature Hot Reload, so changes will be displayed immediately when coding is saved, this is the same as when we create a website using PHP, when coding is complete, just call the address in a web browser, the code will appear quickly (Maybe this is the reason why Web Programming, especially PHP still very popular until now). makes it easier because you don't have to wait long because of the compilation process, on the web the process is called an interpreter), Hot reload is similar to that, I don't really understand what process is in hot reload, Hot Reload is not as fast as the interpreter in web programming, but definitely faster than full compilation process, so this feature will save a lot of time.

You can read an explanation about the Hot Reload feature [here](https://flutter.dev/docs/development/tools/hot-reload "Flutter Hot Reload")
 
### **Made by Google**

As a large company that often creates multiple projects that end up shutting down before release , it's not a guarantee every Google-backed project will survive, but for Project Flutter & Dart, I think it will be one of the many long-lived projects supported by google (At least it can survive because nothing lasts forever), this is because there is currently no hybrid concept that performs close to native, the idea of running a program on canvas like a game is indeed faster than running an application using a web engine, I'm not saying the web engine is bad but I believe the flutter concept provides faster performance than that, not to mention Fuschia OS which was developed by Google using Flutter Framework as the base OS (although I'm not sure this Fuschia OS will run long-lasting as well as flutter), plus flutter can now run on multiple platforms (Windows, Linux, Web, Android, iOS and MacOS) with Thus, it can save production costs in developing applications on multiple platforms.

### **Write Once, Run Anywhere**

It sounds classic and very familiar right 😁 ? Flutter actually has the right to bear that slogan, at the time this article was written Flutter can already be run on many platforms including Android, iOS, Linux, MacOS, Windows and even the Web, with the same code and running on many platforms without any problems it's amazing, although there are some code tweaks if you want to run Flutter on multiple platforms at once (usually code related to the native functionality of that platform, or a library that only supports platform specifics), it's still easier than building an app with a different programming language on each platform.

### **Faster performance**

I won't give exact data about how fast Flutter is compared to Native (like Kotlin) You can easily search the internet about this Flutter benchmark compared to other Frameworks and Native Hybrids, Most of the results definitely show flutter speed which is almost close to Native performance, But what I want to tell you now is about application performance in the real world, early last year I got an application development project where the application already existed using Android Native Kotlin, then for some reason the application had to be remade because it followed a very significant change in business processes, then I developing new applications using Flutter Framework, the result is that the client does not feel a change in performance with the old application, the only drawback is that the old application that uses native has a size 3x smaller than the new application with Flutter, Indeed in terms of size it must be acknowledged native is smaller than Hybrid, but currently the size difference is not too big (around 10-20Mb) it will not be a barrier, smartphones are now equipped with a lot of large storage media with a faster internet connection than smartphones 5 years ago.
 
### **Easy to maintain**

Before anyone disagrees and gets angry because of this point, I once again state that this is my opinion, you can agree or disagree because this I got from personal experience, I am currently doing maintenance on several mobile applications, there are cases where in Mobile app built using Kotlin (Native) SDK it should be updated, here I found many issues including new configuration and library no longer support latest version of Android SDK. But in Flutter Framework maintenance is bit easier, when updating Android SDK, I only need to adjust the configuration a little on the Android part, As for the library because following flutter becomes a bit easier, even if the flutter library doesn't support the latest flutter version, I can easily found a replacement at [pub.dev](https://pub.dev "pub.dev") (The library market for darts and flutter).

Those are 5 reasons why I really like Flutter Framework, and this will be my reason to keep using Flutter, at least the next 5 years I'm very sure Flutter will still be reliable, I don't invite you to switch to Flutter, this article is my notes that I feel for 3 years using Flutter Framework, because for me personally, there are 2 keywords that I will always remember about programming is:
 
>Client: *They will not ask what programming language you use, even you using super advanced programming language of this century or even old programming language, Client will not care about it as long as Client Problem is solved and simplified, Client will accept it*.
 
>Developer: *You don't have to listen to what and why other programming languages are good, as long as you are comfortable using that, client's needs are met, and you make money from that, do it, don't switch away without you knowing the benefits to you, because the result is for you and your family, not anyone else*.
 
Thank you for reading this article.
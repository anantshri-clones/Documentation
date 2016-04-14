# MobSF: Mobile Security Framework

### How to Use with AndroidTamer

__MobSF is preconfigured in the AndroidTamer Pacakges__

Launch MobSF via 

	android@tamer$ mobsf

At this point you can see the console output, for first time it will create folder in ~ i.e. user home directory.

A folder is created in ```~/.mobsf/``` which will contain the file


__Note:__ Remember you don't need to run this command as sudo. Run this as normal user.


### How is it different from Original Source Code

Original sourcecode: [https://github.com/ajinabraham/Mobile-Security-Framework-MobSF](https://github.com/ajinabraham/Mobile-Security-Framework-MobSF)

Modified sourcecode: [https://github.com/AndroidTamer/Mobile-Security-Framework-MobSF](https://github.com/ajinabraham/Mobile-Security-Framework-MobSF)

Major difference is in the approach how tool will store data. In original Code author assumes the standard play that user will git clone and then all data will be stored inside the folder. However for distributions thats not how we wanted it to work so the code that we modify is mainly the settings file where we ensure all data that needs to be dynamic in nature is sourced from the users home directory and not the default location.

This allows flexibility that multiple users can run mobsf and have there own results. This also allows us to keep mobsf updates as distinct as possible.

### Things to keep in mind

1. Don't run the command as sudo user.
2. IF you get error messages around


### Software Details
#### Author: Ajin Abraham
#### URL: [https://github.com/ajinabraham/Mobile-Security-Framework-MobSF](https://github.com/ajinabraham/Mobile-Security-Framework-MobSF)

From the website itself

	Mobile Security Framework is an intelligent, all-in-one open source mobile application (Android/iOS) automated pen-testing framework capable of performing static, dynamic analysis and web API testing. http://opensecurity.in

### Additional References

![nullcon-slides](http://www.slideshare.net/ajin25/nullcon-goa-2016-automated-mobile-application-security-testing-with-mobile-security-framework-mobsf)

![cocon-slide](http://www.slideshare.net/ajin25/automated-security-analysis-of-android-ios-applications-with-mobile-security-framework-c0c0n-2015)

![g4h-webcast](http://www.slideshare.net/ajin25/g4h-webcast-automated)

### TODO for Guide

1. Add images to show how process works
1. Link to the official guide or write your own
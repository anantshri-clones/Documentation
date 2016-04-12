# Decompiling Application

### how to decompile application in AndroidTamer

Android Tamer has all the tools required to perform the application analysis manually however we have gone one step ahead and added more automation to reduce the time spend on remembering command and running them.

To decompile application in AndroidTamer

```android@tamer$ apk2java <apk>```


This will give you a folder structure as shown below

TODO IMAGE

Here ```smali``` folder contains the smali version of the source code
where as `src` folder contains two subfolder `jad` and `jadx` containing source codes decompiled via these two decompilers respectively.

TODO: Geany Screenshot showing two different representation

### Can other distributions use it

Yes, glad you asked [follow steps outlined here](repo_configure.md) 


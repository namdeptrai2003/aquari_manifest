<img src="https://img.xda-cdn.com/hS4G8qQWdvim20S6r5ogbYQG7-U=/http%3A%2F%2Fi.imgur.com%2FymEqc4F.png"> 

Aquari-OS
=========

Credits 
-------
 * [**AOSP-CAF Team**](https://github.com/AOSP-CAF)
 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns) 
 * [**AOSPA**](https://github.com/AOSPA)
 * [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
 * [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
 * [**Pure Nexus**](https://github.com/PureNexusProject)
 * [**OmniROM**](https://github.com/omnirom/)

Getting Started 
--------------- 
To get started with the Aquari-OS sources, you'll need to get 
familiar with [Git and Repo](http://source.android.com/source/version-control.html). 

Initialize the Repositories 
---------------------------

    repo init -u https://github.com/aquarios/manifest -b a7.1.2
    repo sync -j16 

This will initialize the new repository and begin the initial sync. This can take a while!

Building the System 
-------------------

     . build/envsetup.sh
     lunch aquari_<device>-userdebug
     brunch <device>
```

Many thanks to all the amazing people who have patiently helped me along the way!!!

##:)

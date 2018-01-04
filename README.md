openFrameworks addon for capturing video from Point Grey Research's Camera using FlyCapture SDK.

https://www.ptgrey.com/flycapture-sdk

This addon is tested under Windows only.
(note:SDK for OSX is not provided.)

features not implemented currently
* request frame size
* pixel format

# How to use

* Install FlyCapture SDK windows 64bit
* copy header files inside C:\Program Files\Point Grey Research\FlyCapture2\include\ to ofxFlyCapture\libs\FlyCapture2\include
* sub-folder "C" is not necessary.
* copy library file C:\Program Files\Point Grey Research\FlyCapture2\lib64\vs2015\FlyCapture2_v140.lib to ofxFlyCapture\libs\FlyCapture2\lib\vs\x64\ and rename into FlyCapture2.lib

![](https://i.gyazo.com/977d45d33c98e66cf8acfd3909daf314.png)


* I recommend to use Project Generator. It is easy to setup include and library path
* To launch your app, FlyCapture2.dll should be in same folder of your exe file.

I don't know much about software license, but it seems better not to redistribute headers and libraries.
http://www.ptgrey.com/Content/Images/uploaded/FlyCapture2Help/flycapture/07legal/softwarelicenseagreement.html

# tested devices

* Grasshopper3 GS3-U3-23S6M (mono, USB3)
* Blackfly BFLY-PGE-13S2M (mono, GIGE)
* FireFly MV FMVU-03MTM-CS (mono, USB2)

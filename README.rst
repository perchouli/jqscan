jQScan
=====
用Javascript编写的Android程序，扫描条形码查询零食/饮料的价格。

Requirements
------------
	* Android SDK: http://developer.android.com/sdk/index.html
	* Phonegap: http://www.phonegap.com/
	* jQTouch: http://jqtouch.com/
	* Zxing: http://code.google.com/p/zxing/
	* phonegap-plugins: https://github.com/phonegap/phonegap-plugins/tree/master/Android/BarcodeScanne
	* Ant: http://ant.apache.org/

Resource
-----
	* ICON: http://developer.android.com/guide/practices/ui_guidelines/icon_design.html
	* Install Phonegap: http://www.phonegap.com/start#android


Command
-------
./android

android create avd -n gPhone -t android-7

mksdcard 60M ~/sdcard.img

emulator -avd gPhone -netspeed edge -sdcard ~/sdcard.img

#droidgap wiz

ant debug

adb -e install -r bin/jQScan-debug.apk


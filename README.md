Tongseng
========

Tongseng is a [TUIO](http://tuio.org) multitouch tracker for Mac OS X touchpad devices. This 
application allows to use the internal trackpad (or alternatively an external magic trackpad or magic 
mouse) to send TUIO events to your multitouch application.

The current development version also enables alternative TUIO/TCP and TUIO/WEB transport methods in 
addition to the default TUIO/UDP transport.

Usage
-----

1. Download [the application package](https://github.com/fajran/tongseng/releases/download/0.5/Tonseng-0.5.zip) 
   (Universal i386/x86_64 Binary, Minimum MacOS X version 10.6)
2. Open it
3. Run Tongseng
    
    ![Tongseng](tongseng.png)
    
4. optionally change the TUIO/UDP port and host
5. optionally select an internal or external trackpad
6. Click the Start button to activate Tongseng

Then..

1. Run your TUIO-based multitouch application
2. Start touching your touchpad!

Compilation
-----------

### GUI Application

1. Retrieve the code. Using git

        $ git clone git://github.com/fajran/tongseng.git
    
    or by clicking [the download
	button](http://github.com/fajran/tongseng/tarball/master).

2. Open `TongsengApp/TongsengApp.xcodeproj` with Xcode.
3. Build the project.

### Command line application

1. Retrieve the code
2. Go to the source directory
3. Type `make` and return.



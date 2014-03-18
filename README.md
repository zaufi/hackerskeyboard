How to build
============

1. checkout the sources

    $ git clone https://github.com/zaufi/hackerskeyboard.git
    $ cd hackerskeyboard

2. setup path to Android SDK you have  

    $ android update project -p . -t android-16

  where `android-16` is a target Android version (16 is for version 4.1.x)

3. build debug version

    $ ant debug

4. install to the target device (make sure device is connected via USB and install from unknown sources is enabled):  

    $ adb install bin/hackerskeyboard-debug.apk

  add `-r` option for further reinstalls.

BusMan-SAN-IRV
==============
San Diego/Irvine shuttle files

BusManMessages - obsolete messages file.

BusManMessages.json - messages file. Install via
                adb shell mkdir /sdcard/BusMan
                adb push BusManMessages.json /sdcard/BusMan

busman-debug.apk - BusMan app. Install via
                adb install -r busman-debug.apk

ShuttleManForwarderExperimental.apk - "trampoline" app
                forwards old NFC tags to the current
                BusMan app


# SMC

Smart mobile service control with SMS & Sensor Android Application is to control various android mobile operation such as data connection, Wi-Fi, Bluetooth and GPS on/off etc. with a single SMS. With this apps a user can on/off the features that will reduce power consumption. This application is useful for security purpose without any user interaction. It will help when one cannot find his/her mobile i.e., when it is kept in a silent profile mode, it can be automatically activated to the general mode through a message. It will change any profile mode (e.g. silent) to another one mode (general/outdoor etc.) when the received message is matched with the password and command that we stored. If not, it will be as a normal message to the mobile and stored in inbox. Anti-theft alarm protects our phone by creating an alarm sound when someone makes the device unusual move.

# Features
```
    - Turn ON/OFF Mobile Data
    - Turn ON/OFF Wi-Fi
    - Turn ON/OFF Wi-Fi Tethering
    - Change Wi-Fi Tethering Password
    - Change Ringer Mode
    - Turn ON/OFF GPS
    - Clean Phone Memory
    - Clean Memory Card
    - Delete Call log
    - Delete Receivecall log
    - Delete Misscall log
    - Delete Dialcall log
    - Delete Message
    - Get Mobile details
    - Get Contact number
```
# Command list

        silent  : Change one mode to Silent
        normal  : Change one mode to Normal
        vibrate : Change one mode to Vibration

        dataon  : Enable Mobile Data
        dataoff : Disable Mobile Data

        wifion  : Turn on WiFi
        wifioff : Turn off WiFi

        bluetoothon  : Enable Bluetooth
        bluetoothoff : Disable Bluetooth

        gpson  : Enable GPS
        gpsoff : Disable GPS

        format sd: Format Internal Memory
        format mem: Format External Memory

        powermodeon: Enable wifi and data
        powermodeoff: Disable wifi and data

        hotspot : Enable Mobile Data
        syntax : OLD PASS hotspot
        syntax : OLD PASS hotspot, CUSTOM PASSWORD,
        example : 12345678 hotspot,4887asda234$$,

        getdeviceinfo: Get the device info

        getno,name: Get the Contact No

        delsms: Delete Messages
        dellog: Delete Call logs

        delmiss: Delete Miscall logs
        deldial: Delete Dialcall logs
        delreceive: Delete Receivecall logs

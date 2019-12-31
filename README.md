# WLED - Domoticz Python Plugin
Python plugin for Domoticz to add integration with [WLED](https://github.com/Aircoookie/WLED) project

# All work done by  frustreermeneer, I just added support for RGBW LED's.
I have never looked at a python script before, never mind edit one, there is most certainly a better way to implement the option for RGBW LED's but it works.

## BETA
This is my first project in Python and my first GitHub repository. Expect errors, but feel free to try, and let me know what you think!

## Installation

1. Clone repository into your domoticz plugins folder
```
cd domoticz/plugins
git clone https://github.com/frustreermeneer/domoticz-wled-plugin.git wled
```
2. Restart domoticz
3. Make sure that "Accept new Hardware Devices" is enabled in Domoticz settings
4. Go to "Hardware" page and add new item with type "WLED"
5. In WLED -> Sync Interfaces: enable UDP Broadcast and turn on notifications (see screenshot below).

Once plugin is started it will create appropriate domoticz devices. You will find these devices on `Setup -> Devices` page.

## Plugin update

1. Go to plugin folder and pull new version
```
cd domoticz/plugins/wled
git pull
```
2. Restart domoticz2

## Screenshots

Domoticz switches

![Domoticz switches](https://raw.githubusercontent.com/frustreermeneer/domoticz-wled-plugin/master/screenshot.jpg)

Domoticz settings

![Domoticz settings](https://raw.githubusercontent.com/frustreermeneer/domoticz-wled-plugin/master/settings.jpg)

WLED sync settings

![WLED sync settings](https://raw.githubusercontent.com/frustreermeneer/domoticz-wled-plugin/master/wledsettings.jpg)

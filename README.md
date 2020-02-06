
# Home Assistant Configuration
[Home Assistant](https://home-assistant.io/) on a Intel NUC i7 with hassio.

## Change Log:
=======
* v3.1 - cleanup, hassio version sensors, updates for 0.105.0
* v3.0 - hassio migration + massive cleanup + alro purge
* v2.5 - add unifi UVC-G3-Flex
* v2.4 - upgrade schlages to zwp, add coffee light
* v2.3 - cleaning house + the great wink purge
* v2.2 - move from google cloud to Google Assistant, add zwave stick to prep for wink purge
* v2.1 - enable google cloud, fix glances and add person sensors
* v2.0 - complete re-write with for lovelace

=======

## Issues
* spaces Paul, not tabs...

## To Do
* [issues](https://github.com/itsgiff/hass-config/issues)

## Layout
- The *Home* group is the default_view and shows relevant information I want at first glance.
- The *City* group is a local dashboard with the most useful information about Calgary.
- The *Security* group shows cameras and access to the yard and home.
- The *Info* group is for home infrastructure related items and status.

## Acknowledgments
* Hat tip to [jtscott](https://github.com/jtscott/hass-config)
* All the [Home Assistant examples](https://home-assistant.io/cookbook/) and contributors.

## Devices / Technology
- Intel NUC i7
- Schlage (Allegion) BE469ZP Connect Smart Deadbolt (3)
- Chamerlain MyQ Garage Door
- ecobee3 (8 sensors)
- GE 45604 Z-Wave Technology Outdoor Module (2)
- Google Home (6)
- GOCONTROL WNK01-21KIT (8)
- Harmony Companion Hub
- Nest Protect (3)
- Philips Hue Lights (4)
- Philips Hue Bridge
- Nest Hello Doorbell (1)
- Unifi Cloud Key 2
- Unifi Wireless
- Ubiquiti UVC-G3-Flex 1080p Indoor/Outdoor PoE Camera (9)

## Automations
- Front Door Motion Detection
- Front Gate Open / Close Notifications
- Garage Door Open / Close Notifications
- Home Assistant Update Notification
- HACS Update Notification
- Rear Gate Open / Close Notifications
- Rear Deck Light Sunrise / Sunset with Notifications
- Work Meetings (0365) Lighting Notification (Free/Busy)

# EventGhost-snippets
EventGhost config tree snippets

These are some parts of my EventGhost config tree that I thought might be useful for other people.

EventGhost is a free open source automation tool for Windows. http://www.eventghost.org/

- clock - OSD of the current time or date on long press
- AlarmClock - Allows setting of an alarm within 15min intervals or automatically based on a preset time delay. You will need to set the SchedulGhost.xml folder in Plugin: SchedulGhost under the Autostart branch of the configuration tree. Includes a csv that can be used to easily add multiple SchedulGhost schedules.
- PS3monitor - Shows OSD when the battery on a PS3 remote needs to be changed or when it has been disconnected. The PS3 remote is great, but the battery life is very short, this macro allows you to change the battery before it gets too low for the remote to work and also alerts when the bluetooth connection has been lost and needs to be reset by unplugging and then plugging back in the bluetooth dongle.
- ReceiverControl - Volume and power control of an audio receiver via IR transmitter(TIRA 2.1). Features include volume level OSD, volume presets, volume synchronization. Absolute and relative power state control. Uses data files for persistent storage of volume level and power state. Currently configured for use with Pioneer VSX-518 but it can be modified for use with any compatible receiver.

## Installation
- Download: https://github.com/per1234/EventGhost-snippets/archive/master.zip

As a standalone configuration tree:
- Open the .xml file with EventGhost.
- Customize the event that triggers the macro(s) to your preference.

Adding the snippet to your preexisting configuration tree:
- Open the snippet .xml file with EventGhost.
- Right click on the first item under Autostart(if any)>copy.
- Open the target .xml EventGhost file.
- Right click on Autostart>paste - if the plugin already exists in your Autostart folder then you will have to configure your system to work with both your previous use of the plugin and the snippet
- Repeat until all items under Autostart on the snippet file have been copied to the target file.
- Open the snippet file.
- Right click on the snippet folder/macro in the EventGhost configuration tree>copy
- Open the target file
- Right click on Configuration Tree>paste
- Customize the event that triggers the macro(s) to your preference.


#### Contributing
Pull requests or issue reports are welcome! Please see the [contribution rules](https://github.com/per1234/EventGhost-snippets/blob/master/CONTRIBUTING.md) for instructions.

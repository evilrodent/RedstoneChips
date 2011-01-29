RedstoneChips 0.7
==================

RedstoneChips is a Bukkit plugin that allows you to build custom integrated redstone circuits on your craftbukkit minecraft server.
Circuits can be built with any number of inputs and outputs and with any imaginable structure. RedstoneChips currently consists of
two plugins:

- RedstoneChips-0.7 - The core plugin that handles circuit detection and activation, managing preferences and handling player commands. You must install this plugin to be able to build redstone chips.
- [BasicCircuits-0.73](http://github.com/eisental/BasicCircuits) - The basic circuit package containing many different circuit classes. Check out the circuitdocs for more info. In the future, different circuit packages might be available but for now you must install BasicCircuits to have any circuit classes to choose from.

__For much more information, visit the [RedstoneChips](http://eisental.github.com/RedstoneChips) site.__

Installation
------------
* If you're updating from a previous version, delete any previously installed RedstoneChips and BasicCircuits jar files and rename your <craftbukkit>/plugins/RedstoneChips-XX folder to RedstoneChips-0.7 (or delete it to remove previous settings).
* Download the [RedsoneChips-0.7](https://github.com/downloads/eisental/RedstoneChips/RedstoneChips-0.7.jar) jar file.
* Download the [BasicCircuits-0.73](https://github.com/downloads/eisental/BasicCircuits/BasicCircuits-0.73.jar) jar file.
* Copy the downloaded jar files into the plugins folder of your craftbukkit installation, keeping their original filenames.


Changelog
----------
#### RedstoneChips 0.7 (27/01/11)
* Completely new circuit detection algorithm. Circuits can now be built in almost any shape.
* New storage format for the active circuits file (now named redstonechips.circuits).
* Interface blocks replace the output block used by circuits such as pixel, print and synth. More than one interface block per chip is now possible. Interface blocks are placed the same way as input and output blocks and they're indicated by a block of material interfaceBlockType (also added to preferences).
* Fixed print order of binary numbers. LSB is now the rightmost character.
* Missing output levers will now cause an error message to be displayed.
* Output levers will now turn off after a circuit is destroyed.
* A circuit will now deactivate when one of its structure blocks burns down.
* Chat colors are added to the preferences file and can be modified using /redchips-prefs.

#### RedstoneChips 0.6 (24/01/11)
* new command /redchips-debug for getting debug messages from a circuit.
* new command /redchips-pin for getting info about a specific chip pin.


#### RedstoneChips 0.5 (22/01/11)
* improved circuit detection algorithm.
* improved performance of circuit destruction.
* circuits are now destroyed when one of their blocks get exploded.
* new /redchips-classes command.
* renamed active circuits list command to /redchips-active
* new /redchips-prefs command, for viewing and editing the preferences file from within the game.    
* moved plugin files to the plugin folder.
* preferences are now a yaml file.
* added color to player messages.
* fixed error message when creating a bit-set circuit with no outputs.
* catching concurrent modification exception when setting lever data

#### RedstoneChips 0.4 (20/01/11)
* temporary fix for the button bug.
* better performance when working with a large number of circuits.




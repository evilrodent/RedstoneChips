RedstoneChips 0.4
==================

<div style="float:right">
<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypal.com/en_US/NL/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>
</div>

A Bukkit plugin for building custom integrated redstone circuits with any number of inputs and outputs.
This is the core RedstoneChips plugin consisting of only the essentials. 
To actually build ICs you need to download and install the [BasicCircuits](http://github.com/eisental/BasicCircuits) plugin. 

![counter example circuit](http://github.com/eisental/RedstoneChips/raw/master/images/above.jpg "note block sequencer")

Install
--------
   * Copy jar file to the plugins folder of your craftbukkit installation.
   * Install at least one circuit package plugin.

After running craftbukkit with the plugin for the first time, a redstonechips.properties file is created in the server root folder with default plugin settings.

You can change the block types used to construct a circuit by editing this file. Default values are gold block for outputs, iron block for inputs, and sandstone for the circuit body.
Type is NOT case-sensitive and can be any bukkit block material name. any already activated circuit will stay activated even after it's block types are invalid.

How to build an IC
-------------------
   Every IC is made of a line of blocks with input and output blocks to the left or to the right of the line. 
Place a lever on the block next to each output block. Next place a wall sign attached to the first main block of the circuit with the circuit class name on the first line of text, and any additional arguments on the next lines.

   Once the IC is built, right-click the sign to activate it.

* Any block that can send a redstone current (redstone wire, redstone torch, button or lever) can be placed on the block next to an input.
* Input and output numbering starts from the sign onwards. i.e. input/output 0 will be the ones closest to the sign.
* The main line can be of any length and input and output blocks can be placed anywhere along this line, on both sides. 

Here's an example 4-bit counter chip with 2 inputs and 4 outputs (looking from above, each letter represents one block):  
* b - main block (sandstone by default) * i - input block (iron block by default) * o - output block (gold block by default) * l - lever on any block face * s - wall sign attached to the main block

	    s	    
	l o b i
	    b
	l o b i
	    b
	l o b
	    b
	l o b


sign text (on first line):
	counter


This will create a clock circuit with 2 outputs and 2 inputs. When the block left to one of the input blocks receives a high redstone current the corresponding output will start to blink, turning on every 2 seconds.

The 4-bit counter:
![counter example circuit](/eisental/RedstoneChips/raw/master/images/counter.jpg)

For more info check the [BasicCircuits](https://github.com/eisental/BasicCircuits/wiki/BasicCircuits-) Wiki.

Destroying an IC
-----------------
You can destroy an IC by breaking one of its structure blocks, including the output levers.

Commands
---------
   * /redchips-list	Message the player with a list of every currently activated circuit in the server.


Changelog
----------

##### 20/01/11 RedstoneChips 0.4
* temporary fix for the button bug.
* better performance when working with a large number of circuits.





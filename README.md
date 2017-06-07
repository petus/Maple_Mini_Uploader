#Maple Mini Uploader<br>
made by Petus (c) 2015<br>
https://chiptron.cz or https://time4ee.com<br>
<br>
Instructions:<br>
	Install dfu-util from http://dfu-util.sourceforge.net/ <br>
		v0.8. I didn't try latest version<br>
		(http://dfu-util.sourceforge.net/releases/)<br>
	I tried Maple Mini in Perpetual Bootloader Mode (http://docs.leaflabs.com/docs.leaflabs.com/index.html)<br>
		- Plug your board into the USB port.<br>
		- Hit the reset button (it’s the button labeled RESET). Notice that your board blinks quickly 6 times, then blinks 
    slowly a few more times.<br>
		- Hit reset again, and this time push and hold the other button during the 6 fast blinks 
    (the normal button is labeled BUT). You can release it once the slow 			blinks start.	<br>
	Copy *.bin file from your IDE (for the same microcontroller like in Maple Mini) into this direction and 
  run executable maple_mini_uploader file. Only one *.bin file can be in this direction!<br>
<br>
Command:<br>
	sudo bash ./maple_mini_uploader<br>
<br>
Version:<br>
	v0.1 - First version - made by Petus<br>

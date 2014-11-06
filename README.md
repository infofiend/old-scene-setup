switch-control-4-hues-switches
==============================

This is a Smartthings app that 

  1) monitors a switch (virtual ok) to trigger on or off 2 groups of hue lights &amp; and 2 groups of switches.
  2) Each set of hue lights can have different light settings
  3) App also checks for no motion to turn off lights for desired time
  
*****
  
  I use this app to set lighting "scenes" for any room in my house.  There are 3 steps involved:
  
  i) I create a virtual switch (using the standard "on/off button" device type).  
  ii) I cause that virtual switch to be activated by one or more triggering events -- e.g., mode, another switch, presence, time of day, etc.  
  iii) I use this app to turn on the selected lights (my "scene") if that virtual switch turns on.      
  
  For example, I created a virtual switch called "LR Morning Scene."  I have it triggered at 7 am, by motion in my Living Room motion detector after 6 am), or by the Front Door opening (the Hue Mood Lighting app is great for this type of switch control because it already contains the code for multiple triggering events).  Regardless of the triggering event that causes the "LR Morning Scene" switch to turn on, this app then triggers the LR lighting scene I designed for morngings only.
  
  I like this setup because it separates the triggers from the actions, thereby giving my home setup much more flexibility.
  
  

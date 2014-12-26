SCENE CONTROL (Completely Automated Smart Lighting Control)
==============================

  SCENE CONTROL is a Smartthings app that monitors the state of the specific switch to implement a lighting "Scene" - up to 2 different groups of Hue lights &amp; 2 different groups of switches.  Each group of Hue lights can have different light settings (level & color) that is independent from the other.  Each group of switches is similarly independent and can set to on/off 
 
  SCENE CONTROL -- in combination with a dedicated switch (physical or virtual) and the "GLOBAL TRIGGER" app (SEE HERE) -- can be used to set up very flexible -- and completely automated -- smart lighting "scenes" for every room in your house.  The process is: (1) Set up Scene Switch (physical or virtual), (2) Set up GLOBAL TRIGGER app to turn on Scene Switch, and then (3) set up SCENE CONTROL app to implement the actual lighting of the Scene.  
  
  SCENE CONTROL can also check for "no motion" events and then turn off (reduce the level to 0) the Hue group(s) and/or the switch group(s) based on the amount of time you specify.
  

** ** ** ** EXAMPLE ** ** ** **

  STEP 1) From within the IDE, create a virtual switch (if you are using physical switch, then just go to next step) using Smartthings' standard "on/off button" device type.  
IMPORTANT -- Each scene will need its own switch.  For example, I created 4 separate virtual switches for the 4 scenes I like in my bedroom:  "Bedroom Morning Switch," "Bedroom Day Switch," "Bedroom Night Switch," and "Bedroom Late Switch."

  STEP 2) From within the Smartthings App, add a "SCENE CONTROL" app and identify the lighting / switches that you want on/off. IMPORTANT - again, you will need to add a separate SCENE CONTROL app for each scene that you have!  For example, I added 4 separate SCENE CONTROL apps for my 4 bedroom scenes:  "Bedroom Morning Scene," "Bedroom Day Scene," "Bedroom Night Scene," and "Bedroom Late Scene.
  
  STEP 3) From within the Smartthings App, add a "GLOBAL TRIGGER" app and identify the events that turn your Scene switch on/off.  The TRIGGER app allows you to select multiple triggering events -- e.g., switches, presence, time of day, contact, moisture, buttons, etc.  
IMPORTANT - again, you will need to add a TRIGGER app for each scene that you have!  For example, I added 4 separate TRIGGER apps for my 4 bedroom scenes:  "Bedroom Morning Trigger," "Bedroom Day Trigger," "Bedroom Night Trigger," and "Bedroom Late Trigger.

  
  OPTIONAL) In order to avoid having multiple triggers firing at once (creating chaos), I recommend setting up a different GLOBAL TRIGGER for each mode -- i.e., specify the specific mode(s) in each TRIGGER app so only 1 TRIGGER app controls at any time.  If you do limit it this way, however, and you also want the scene to change immediately when the mode changes, then you will need to turn on the Scene switch with something else.  I use "Hello Home" actions.  For example, I set up a "Late" Hello Home action to run at midnight that (1) changes the mode to "Late" and (2) triggers my "Bedroom Late Switch" (as well as my "LR Late Switch" and my "Outside Late Switch").
 

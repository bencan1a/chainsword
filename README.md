Customized Chainsword based on MysteryMaker Chainsword original.

These are some customiuzed STLs for a remix of the original Imperial Chainsword by Marko at MysteryMakers (go subscribe to his Patreon! https://www.patreon.com/c/mysterymakers/posts) The files here will be useless without those originals. 

All of this is provided free, but with no guarantee whatsoever. I made this for my own enjoyment. If others find some value in it, that's great. And again - go subscribe to MysteryMakers. They are awesome. 

Most of the changes are in the MidBody and Handle portion of the build. 

**The Handle:** 
* STLs
  * **G2 Long**, **G5** and **G6** are modified to include space for a microswitch and a new handle assembly.
  * The new Handle consists of **SkullHandle**,**SkullCap**, **Dowel** and **L Dowel Plug** and **R Dowel Plug**
* Assembly
  * When printing SkullHandle, pause the print midway through and insert a spring into the interior cavity, with one arm of the spring sticking up.
  * Insert Dowel through SkullHandle and glue it. I put rubber bushings around the protruding dowel ends to make a snug fit that still rotates when the handle is inserted in the slot in G5.
  * Insert SkullHandle plus Dowel and Bushings into the slot in G5, pushing the spring arm up into the hole in G5. This allows the handle plus dowel to insert into the slot in G5 and the spring provides some pushback.
  * Use L and R Plug Insert to hold the handle in place. There's a hole for a self tapping screw there. 
  * SkullCap.stl is the little skull on the end of the handle. 
* Notes -
  * the trigger handle is a little loose and I ended up putting silicone bushings in there to firm it up a bit. You'll need to fiddle with it to your liking.
  * Spring tension is important - use a stronger spring than you think.
  * You need to get the placement of the microswitch just right to enable the handle to hit it when squeezed and release when not. This took some fiddling and I'd priobably design it different if I was doing it again. Fiddle with it before you glue the microswitch in place. 
  * The clearance for your hand isn't as wide as I'd have liked. If I had it to do over again I'd extend the height of the guard (G2 Long and Short) to provide more room for your hand to fit comfortably.
 
 **The MidBody**
 The midbody is where the electronics go and gets some extensive modifications:
 * STLS are:
   * M1 - the big body
   * M6 - modified to use magnets to cover the soundboard socket
   * Brainboard - screw soundfx board to this, lipoly battery slides underneath. Magnets in floor of M1 hold it in place. 
   * PowerSwitch Cover - The slider to turn on and off the power
   * PowerSwitch Plug - print this in TPU and use it to stick the PowerSwitch Cover onto the SPDT Slide switch.
   * Speaker Cover Body and Cap - covers the speaker and provides holes for sound.  
    
* Electronics
  * BOM
    * Lever Microswitch
    * AdaFruit SoundFx Board (which is screwed onto Brainboard.stl)
    * AdaFruit 40mm 5W Speaker (hot glued to the Speaker Cover Body)
    * AdaFruit PowerBoost 500
    * SPDT Slide Switch
    * Small LiPoly Battery
  * Assembly:
    * Solder the Powerboost onto the SoundFx board directly.
    * Connect the SPDT slide switch to the switch connectors on the powerboost using wire leads. (I used dupont connectors to allow for disassembly but it makes it tight in there. Not sure if there's a better solution assuming you want to be able to remove the brain.)
    * Place Microswitch in the slot in G6, and feed the leads back into M1 using the channel provided. Leads need to be long to make that run.
    * Solder (or use dupont connectors) the connection between microswitch and 00 pin and GND pin on soundfx.  
    * Slide Switch goes in the slot in M1. Put the PowerSwitch Plug on the switch slider and then the Powerswitch cap over that.
    * Solder the speaker connector to the SoundFX board and connect it to the 40mm speaker.
    * Glue together the Speaker Cover Body and Cap, then hotglue the 40mm speaker in there.
    * Connect Speaker wires to SoundFX board.
    * Connect LiPoly Battery to PowerBoost and charge it all up.
  *   Notes
    * It's tight inside M1, sorry.
    * You can program the powerboost to play whatever sound you like. I used the sustain sound type so that it'd run as long as the trigger was squeezed and turn off when released. I searched the web for chainsaw sounds and found some really good revving chainsaw ones.
 
Wall Hanger
  * You will want some sturdy wall hangers. I bought these on Amazon: https://a.co/d/g0wj1eK
  * Hanger Cover sits on top of the metal wall hangers. It has a big slot for the tooth of the blade to go into.
  * Face Plate is the front of the hanger. It slots onto the Hanger Cover nice and tight. 
  * Bottom Cover goes on the bottom to hide the metal hanger.
 

   

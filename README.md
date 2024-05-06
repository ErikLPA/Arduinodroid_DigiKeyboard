# DigiKeyboard
Digispark's DigiKeyboard library for ArduinoDroid IDE.  

**NOTE:** This library is fetched from official digistump repo:  
https://github.com/digistump/DigistumpArduino/tree/master/digistump-avr/libraries/DigisparkKeyboard 

Code is verbatim, just files are re-arranged and properties file is add, in order to make use in Arduino Droid.  

 Digistump AVR board manager package:
 this link does not work as of 05-05-2024:
 
 http://digistump.com/package_digistump_index.json
 
 this link still works
  https://github.com/ErikLPA/Arduinodroid_DigiKeyboard/blob/main/package_digistump_index.json

# USAGE:
 The code format is same as official DigiKeyboard.h, if not sure checkout the examples and original Documentation:  

1. After writing the code, compile it first.

2. Set the board type to Digispark:  
menu(triple dot) -> settings -> Board type -> Digistump -> Digispark.

3. Now, you can flash this to Digispark:  
menu(triple dot) -> Actions -> upload -> *upload over USB.  
OR Simply Shortcut icon on the top of the editor.
  
\* You get only 4 seconds to press "upload over usb" just after detection of  the Digispark.

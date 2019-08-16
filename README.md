# gsm-gps-tracker
A simple GSM GPS and payload data tracker unsing an Arduino with sim800l and Ublox Neo 6m module. On the server side php and mysql.

## Getting Started
1. Put the content of the "Php Code" to the webroot of your webserver.

2. Run the sql on your database tool of choice. (of course on the same machine as the php code is ;) )
 
3. Install all libs via the Arduino 'Library Manager':
  
<TinyGPS++.h> by arduiniana.org
  
<TinyGsmClient.h> by Volodymyr Shymanskyy
  
<SoftwareSerial.h> buildin by Arduino
  
## The Hardware
You will need some hardware ... 
  
  1. Arduino Pro Mini (3,5 Euro)
  
  2. GSM SIM800L Module (12 Euro)
  
  3. Ublox Neo m6 GPS Module (8 Euro)
  
  4. 3.7V LiPo Battery (USB wont work as the GSM module draws around 2A peak while transmitting)
  
  5. Optional: My PCB

## Warning
The charge lipo circuit is not functional. Just ignore the corresponding SMD parts on the top part of the PCB.



## some PCB images
![PCB Backside](/Images/backside.jpg)
![PCB Frontside](/Images/front.jpg)
![PCB raw A](/Images/pcbA.jpg)
![PCB raw B](/Images/pcbB.jpg)



Best regards, hava fun, 

Neumi

# Wireless-Notice-Board
A wireless notice board built using Arduino UNO, GSM module and LCD display that conveys messages directly from user's phones onto a remote screen.  

* Arduino UNO is the programmed interface between the GSM module and lcd display.  
* The program initializes the two peripherals upon startup. Arduino then continuously monitors the module to check whether a message is received and upon receiving a message, transmits it to the lcd display.   
* In this way, a message sent from a user's phone to the module, gets displayed on a remote screen.

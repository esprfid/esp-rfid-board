# ESP12 / ESP12F / ESP12E / ESP12S Wiegand rfid board

Small ESP12F breakout board, custom built for Wiegand RFID readers.

### You can get this board from my Tindie shop:
<a href="https://www.tindie.com/stores/nardev/?ref=offsite_badges&utm_source=sellers_nardev&utm_medium=badges&utm_campaign=badge_large">
<img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104">
</a>


WARNING: Although it’s rated for more than 12V, i strongly suggest to use maximum of 12V input!

Check the image for explanation of how to hook up the reader

<img src="https://raw.githubusercontent.com/nardev/esp-rfid-wiegand-board/master/images/esp-rfid-wiegand-board.png" width="" />&nbsp;&nbsp;

** There is a resistor on the way from ESP to buzzer due to strange behaviour of busser that ditn't react to HIGN/LOW except if there is a resitor on the way from ESP to Wiegand reader.

Custom pads

<img src="https://raw.githubusercontent.com/nardev/esp-rfid-wiegand-board/master/images/esp-wiegand-rfid-05.jpg" width="250" />&nbsp;&nbsp;
<br>
** New board has marked pads

**Option 1:**
Solder 2 and 1 on both pads results in passing “Ring” tactile switch/button to ESP8266 pin GPIO14

**Option 2:**
Solder 3 and 2 on both pads results in passing “Ring” switch to a terminal on  another side of board.

**Option 3:**
Solder 1 and 3 on both pads results in passing terminal pins to ESP8266 GPIO14, planned so that you can hook door status magnet sensor. In this case, you can’t use “Ring” button in Option 1. or 2.


<img src="https://raw.githubusercontent.com/nardev/esp-rfid-wiegand-board/master/images/esp-wiegand-rfid-04.jpg" width="" />&nbsp;&nbsp;

<img src="https://raw.githubusercontent.com/nardev/esp-rfid-wiegand-board/master/images/esp-wiegand-rfid-03.jpg" width="280" />&nbsp;&nbsp;
<img src="https://raw.githubusercontent.com/nardev/esp-rfid-wiegand-board/master/images/esp-wiegand-rfid-02.jpg" width="280" />&nbsp;&nbsp;
<img src="https://raw.githubusercontent.com/nardev/esp-rfid-wiegand-board/master/images/esp-wiegand-rfid-01.jpg" width="280" />&nbsp;&nbsp;

* BOM has some mistakes, contact me if you need some help.

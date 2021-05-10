<h1>#Lighthack</h1>

These are projects based original on the #lighthack project from ETC https://github.com/ETCLabs/lighthack<br>
You find further informations also in the ETC forum https://community.etcconnect.com/etclabs/f/lighthack<br>
Code is based on Box2A and Box2B by Stefan Staub https://github.com/sstaub and box1 from ETC<br>
All projects uses an Arduino Arduino UNO, but also an Arduino MEGA gives you connection to your console. <br>
On nomad you can use other boards, but you have to figure out which works.

<h1>Important Notes</h1>
Pinout for the Encoder wheels is slightly different from the EOS box1 code. <br>
This code uses <b>A0, A1, A2, A3</b> respectively for encoder wheels and I am unable to find where to change this in the code.
<br><br>
This also requires the encoder button connections to be soldered in and connected to function. Box1 instructions do not include this, and your encoders may vary.
<br><br>
You can select encoder groups in twos from the list provided, Arduino Uno can handle a maximum of 14 parameters (7 pairs). <br>
I leave some blank using none for better grouping. This is entirely flexible. 

<h1>Dependencies</h1>
Requires the Arduino OSC parsing library maintained by the great folks over at CNMAT. https://github.com/CNMAT/OSC<br>
The assembly instructions documents contain details on how to add this to your Arduino project.


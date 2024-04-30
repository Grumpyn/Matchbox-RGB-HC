# Matchbox-RGB-HC
![mbhc](https://github.com/DaiveeCZ/Matchbox-RGB-HC/assets/83717170/4554dd51-c6ec-42d0-8aeb-ee97e7a5cbb7)

Control board for RGB LED strips, based on ESP8266 platform. Powered by DC jack and controlled by Wi-Fi. Option to connect an external IR receiver for additional IR remote control support. Unfinished project at the stage of finished design which should work. However, the board was never manufactured.
### Programming using the external programmer [F_Board](https://github.com/DaiveeCZ/F_Board-V1.1) which I also designed and was successfully built.

### This is a high current/voltage version of [Matchbox-RGB-V2](https://github.com/DaiveeCZ/Matchbox-RGB-V2) which I also designed.
## CAUTION: Board can work with 5/12/24V RGB LED stripes. BUT, for example, if you connect a 5V LED strip to the 12V power input, you will blow it up!!!  Please follow the rule:  LED strip voltage = power supply voltage for the board.

## Pin map:
- 1 - GND
- 2 - 3.3V
- 3 - IR (for external IR receiver)
- 4 - B
- 5 - G
- 6 - R
- 7 - VCC (5/12/24V)
- H1 - VCC (5/12/24V)
- H2 - GND

Can be powered via DC jack connector or big holes in board.



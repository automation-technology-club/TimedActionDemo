# TimedAction Demo 

Based on 3 at once from the TimedAction library.
http://playground.arduino.cc/Code/TimedAction

This has 10 actions and 1 interrupt set. I had the demo running on a Arduino MEGA 2560.

## Usage

Demo to see how far you can push the Arduinos, turns out pretty far, but it did start to slow down over time.  Serial communication almost kills it.
Code on Codebender.cc - https://codebender.cc/sketch:368336

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Based from:
TimedLibrary: http://playground.arduino.cc/Code/TimedAction
OLED code based from 96 OLED SPI display by steve8939
https://codebender.cc/sketch:95019#96%20OLED%20SPI%20display.ino
https://codebender.cc/sketch:100303
DHT11 code based on Ladyada and thatcurtisguy6 code (which was based on other sketches):
https://codebender.cc/sketch:85814#dht11_test_ladyada.ino
https://codebender.cc/sketch:368023
LeRoy Miller (2016).

##Libraries Required
TimedAction.h
NewPing.h
SPI.h
string.h
DHT.h
Wire.h
Adafruit_GFX.h
Adafruit_SSD1306.h

these are easy to find by google or here on github. Also if you use codebender they are already on it.

## License

As far as I am aware this License applies, please correct me if I am incorrect.

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses>

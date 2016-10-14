# ElitePlayer-Rainmeter
Rainmeter player for Elite Dangerous

Very simple rainmeter overlayer.

![alt tag](https://raw.githubusercontent.com/Mindii/ElitePlayer-Rainmeter/master/Img/eliteplayer.jpg)

# Install
1. Get Rainmeter
2. Install ElitePlayer_1.2.2.rmskin
3. Edit config variable "Player" for your player (Elite Player\@Resources\Config.inc):<br>
     foobar2000: Player="CAD" (Needs foo_cad plugin)<br>
     iTunes: Player="iTunes"<br>
     Winamp: Player="Winamp"<br>
     WMP: Player="WMP"<br>
     More players here: https://docs.rainmeter.net/manual/plugins/nowplaying/<br>
<br>
Note: if you use source folder there is folder called Resources add @ in front "@Resources".

# Known bugs
"Foo_Cad" or "Nowplaying.dll" does't show song "Position" when continued with "Next" button, for now insted use "Play" on start.

# Changelog
1.2.2<br>
     Changed update from 1sec to 0.2sec for main load script so song change should be smooth now.<br>
     Player now fades out and in.<br>
     Fixed bug with "WhatTimeIsIt" mesure.<br>
1.1.9<br>
     Config have now own file: Elite Player\@Resources\Config.inc<br>
     Main file should load player when needed, it don't show if game/player is not running.<Br>

# Resize parallax / Readme
- [About](#about)
- [How to use](#how-to-use)
- [Preview](#preview)
- [Todo](#todo)


<br><br>
## About
A subtle window-resize based parallax effect I created for a website concept as a hidden gimmick. <br>
(The real version also had a few GIF-animations with birds in the trees and the sky)

I don't think the effect can be used widely - but if you like it, feel free to copy <br>
the source and create something nice of it. (I would really like to any result)


<br><br>
## How to use
Download all files and open in a new browser (Firefox or Chrome). <br>
You need a big display to see the full animation because of the big images; preferably about 1920×1080px.

Resize the window slowly (lets say about 50-100px per step) and wait a little bit - like 1 sec. - after each step. <br>
The parallax animation will slowly follow the resize direction.

Animation will only start if you the window is smaller than 1900px but wider than 1000px. <br>
This is to keep the footer element always in the center (see screenshot).

#### Requirements
- Any modern browser with CSS transition support
- Last tested with: Firefox 34 and Chrome 39 under Win 7


<br><br>
## Preview
Try it out here: [Resize-Parallax »](http://christianoellers.github.io/Resize-Parallax/)

<br><br>
![Screenshot](/Screenshots/Website-Demo.png)


<br><br>
## Todo
- [x] The first resize does not look good, it quickly jumps ... maybe a problem of using CSS transitions?
- [x] In some cases the resize direction is wrong if resizing from small to big.

Solution: The animation issues come from the timeout. I commented it out and added some tech details in the code. <br>
Feel free to play with the settings yourself.


# The Light Before Xmas

The Light Before Xmas is a simple puzzle game, the point of which is to light up every bulb on the Christmas tree.

Electricity starts at the base of the tree, and flows through connected wire segments.  It is possible to rotate the wire segments and bulbs such that every bulb and wire segment is energized, and every wire segment leads to either a bulb or another wire segment (that is, there are no "loose" wire segments which go nowhere and spark).  See how quickly you can reach that state from the randomized start state!

Clicking on wires or bulbs will rotate them.  If you have a touch screen you can also "flick" them in either direction.

# Building

## Setup
To build The Light Before Xmas, install [Rogue](https://github.com/AbePralle/Rogue) and [depz](https://github.com/MurphyMc/depz), then run one of the commands below in the repo.

## Building

### macOS
Run `rogo macos` on a Mac and then open `Platforms/macOS/Project-macOS.xcworkspace` in Xcode.

### ios
Run `rogo ios` on a Mac and then open `Platforms/iOS/Project-iOS.xcodeproj` in Xcode.

### Linux
Run `rogo linux` on Ubuntu (and possibly other Linux distributions) and then run `Build/Linux/light-before-xmas`.

### Web
Run `rogo web run`.


# About

The Light Before Xmas began as an app for the original iPad written by Murphy McCauley at the end of 2010.  It was inspired by several similar games available on the web which were written in Flash and were therefore unplayable on the iPad.  The original app was never widely released, but nine years later, Murphy and Abe Pralle updated it for modern tablets, phones, and the web.  The basic gameplay mechanic of The Light Before Xmas can be traced back to Zenji, a 1984 video game.  We thank its designer, Matthew Hubbard. 

The Light Before Xmas is written in the Rogue programming language (originally using Rogue's predecessor, Slag) using the Plasmacore game programming framework.  Both Rogue and Plasmacore are open source software under the MIT license, and they are available on GitHub.


# Music

The wonderful music is all by Kevin MacLeod and is available under Creative Commons licenses.

"Dance of the Sugar Plum Fairies" \
Kevin MacLeod (incompetech.com) \
Source: [incompetech.com](https://incompetech.com/music/royalty-free/music.html) \
Licensed under Creative Commons: By Attribution 4.0 License \
https://creativecommons.org/licenses/by/4.0/

"Jingle Bells (Calm)" \
Kevin MacLeod (incompetech.com) \
Source: [incompetech.com](https://incompetech.com/music/royalty-free/music.html) \
Licensed under Creative Commons: By Attribution 4.0 License \
https://creativecommons.org/licenses/by/4.0/

"Oh Christmas Tree" \
Kevin MacLeod (incompetech.com) \
Source: [wikimedia.org](https://commons.wikimedia.org/wiki/File:Oh_Christmas_Tree.ogg) \
Licensed under Creative Commons: By Attribution 2.0 License \
https://creativecommons.org/licenses/by/2.0/

"Silent Night" \
Kevin MacLeod (incompetech.com) \
Source: [incompetech.com](https://incompetech.com/music/royalty-free/music.html) \
Licensed under Creative Commons: By Attribution 4.0 License \
https://creativecommons.org/licenses/by/4.0

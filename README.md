# word-guessing-workspace

This is the Lerna workspace used to build the word-guessing game.

## Installation

You will need to install this project inside the /packages folder of this repository:
- [word-guessing-lib](https://github.com/isirode/word-guessing-lib)
- [word-guessing-game-common](https://github.com/isirode/word-guessing-game-common)
- [word-guessing-solo](https://github.com/isirode/word-guessing-solo)
- [word-guessing-game-multi-xterm](https://github.com/isirode/word-guessing-game-multi-xterm)

You will also need my fork of the [peerjs-server](https://github.com/peers/peerjs-server) project, but this is not pushed yet.

I am also storing this projects, but it is not necessary:
- [word-guessing-solo-pages](https://github.com/isirode/word-guessing-solo-pages)
- [word-guessing-multi-xterm-pages](https://github.com/isirode/word-guessing-multi-xterm-pages)

## Usage

Run `lerna bootstrap --hoist` at every time a package is installed in a sub-package of this project.

## License

It is provided with the GNU AFFERO GENERAL PUBLIC LICENSE.

This is a workspace for the word guessing game.

Copyright (C) 2023  Isirode

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

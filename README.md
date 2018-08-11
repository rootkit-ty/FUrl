# FUrl

## About

### What is FUrl

It's simple, a replacement for URLView that uses FZF for selection
It's currently in a very early state, but I hope to be improving it.

### How does it work

It's a simple bash script that strings together a few existing commands. Checking
that they're installed and changing accordingly.

The regex is ripped straight from URLView, so expect 100% compatibility with matching.

## Installation

### Download

TODO: Add the download link

### Verify

My GPG key can be found at my [Blog](https://rootkitty.tech/pub_key.asc)

`gpg --verify urlf-0.0.1.tar.gz.asc urlf-0.0.1.tar.gz`

### Install

`sudo make install`

## License

    FUrl the Fuzzy URL finder
    Copyright (C) 2018 Ring <3 Rootkitty

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

Full license is found in the `License` file

## Contributing

It's a small project written in very little time, so if you find a problem please
create a github issue.

Feel free to contribute by creating pull requests and such, or just forking it.
Things that need to be done should be listed in the github issues or in the TODO.md

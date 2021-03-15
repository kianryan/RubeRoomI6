# The Puzzle Room

An interactive fiction project using [Inform6](https://www.inform-fiction.org/) and [Vorple](https://vorple-if.com/).

You can play the game [here](https://icy-sky-03dc70b03.azurestaticapps.net/).

## Running The Game

If you fancy running the game on a Z5 interpreter, the included game/RubeRoom.z5 file 
should run fine on any Z5 interpreter.  I built and debugged the game primarily on [Frotz](https://davidgriffith.gitlab.io/frotz/).


## Why can't I run the current version of the game on Frotz?

The Vorple/web enhancements are extensive, and managing a single code branch to handle both
a standard Z5 version and a Vorple enhanced version was not within my constraints.  So 
you get to play the finished version online, and the WIP version in Z5.  Feel free to strip 
out the Vorple enhancements and compile your own for a vanilla experience.

## Compiling

* Install [Inform6](https://www.inform-fiction.org/)
* Install [Vorple](https://vorple-if.com/) extensions

Build:

```
inform6 -SD -c -E1 RubeRoom.inf -G \\$MAX_STATIC_DATA=30000 \\$MAX_LABELS=12000
```

## Contributing

Pull requests _are_ welcome for technical changes, spelling and flow.  Changes to story elements are not welcome.

But you are welcome to fork and do as you please.


## License

Copyright 2021 Kian Ryan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


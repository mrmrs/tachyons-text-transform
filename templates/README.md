# TACHYONS-TEXT-TRANSFORM

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-text-transform
```
or download the css on github and include in your project.

## The Code
```

/*

   TEXT TRANSFORM

*/

.ttc { text-transform: capitalize; }
.ttu { text-transform: uppercase; letter-spacing: .2em; }

@include break(not-small) {
  .ttc-ns { text-transform: capitalize; }
  .ttu-ns { text-transform: uppercase; letter-spacing: .2em; }
}

@include break(medium) {
  .ttc-m { text-transform: capitalize; }
  .ttu-m { text-transform: uppercase; letter-spacing: .2em; }
}

@include break(large) {
  .ttc-l { text-transform: capitalize; }
  .ttu-l { text-transform: uppercase; letter-spacing: .2em; }
}
```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

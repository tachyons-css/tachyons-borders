# TACHYONS-BORDERS

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-borders
```
or download the css on github and include in your project.

## The Code
```

/*

   BORDER BASE

   Legend

   a = all
   t = top
   r = right
   b = bottom
   l = left

*/

  .ba { border-style: solid; border-width: 1px; }
  .bt { border-top-style: solid; border-top-width: 1px; }
  .br { border-right-style: solid; border-right-width: 1px; }
  .bb { border-bottom-style: solid; border-bottom-width: 1px; }
  .bl { border-left-style: solid; border-left-width: 1px; }

@include break(not-small) {
  .ba-ns { border-style: solid; border-width: 1px; }
  .bt-ns { border-top-style: solid; border-top-width: 1px; }
  .br-ns { border-right-style: solid; border-right-width: 1px; }
  .bb-ns { border-bottom-style: solid; border-bottom-width: 1px; }
  .bl-ns { border-left-style: solid; border-left-width: 1px; }
}

@include break(medium) {
  .ba-m { border-style: solid; border-width: 1px; }
  .bt-m { border-top-style: solid; border-top-width: 1px; }
  .br-m { border-right-style: solid; border-right-width: 1px; }
  .bb-m { border-bottom-style: solid; border-bottom-width: 1px; }
  .bl-m { border-left-style: solid; border-left-width: 1px; }
}

@include break(large) {
  .ba-l { border-style: solid; border-width: 1px; }
  .bt-l { border-top-style: solid; border-top-width: 1px; }
  .br-l { border-right-style: solid; border-right-width: 1px; }
  .bb-l { border-bottom-style: solid; border-bottom-width: 1px; }
  .bl-l { border-left-style: solid; border-left-width: 1px; }
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


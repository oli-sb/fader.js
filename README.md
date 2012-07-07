#fader.js

A micro js that fades in and out html elements.

##Usage
###Basics
```javascript
// "elemId" => the id of the element to be faded out
// 5        => the animation duration
Fader.fadeOutWithId("elemId", 5);

// "elemId" => the id of the element to be faded in
// 3        => the animation duration
Fader.fadeInWithId("elemId", 3);

// "elemClass" => the class of the element to be faded out
// 0           => the element index, in the retrieved objects, to be faded
// 4           => the animation duration
Fader.fadeOutWithClass("elemClass", 0, 4);

// "elemClass" => the class of the element to be faded in
// 1           => the element index, in the retrieved objects, to be faded
// 2           => the animation duration
Fader.fadeInWithClass("elemClass", 1, 2);
```

##How to contribute
Please ensure that you provide appropriate test coverage and ensure the documentation is up-to-date. It is encouraged that you perform changes in a clean topic branch rather than a master and that you create a pull request for them. This will facilitate discussion and revision.

Please be clean, keep your commits atomic and with the smallest possible logical change. This will increase the likelihood of your submission to be used.

##License
Copyright (c) 2012 Lukas Alexandre. http://www.devinscene.com.br/

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to use, copy and modify copies of the Software, subject
to the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

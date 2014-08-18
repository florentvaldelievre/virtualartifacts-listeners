Listeners

## Description 

This plugin allows your app to listen to some URLs and schemes. This is for Android only

## Example

You are in your favourite browser and you want your app to appear in the 'Complete action using' list when clicking on a link like <a href="www.example.com">test link</a>
Your app will also appear in the 'share' by defining the mimeType you want to listen to.

## Installation

###  Automatically (CLI / Plugman)

listeners is compatible with Cordova Plugman. Replace the variables according to your needs

cordova plugin add https://github.com/florentvaldelievre/virtualartifacts-listeners.git --variable MIMETYPE_1=image/* --variable MIMETYPE_2=video/* --variable HOST_1=www.example.com --variable HOST_2=example.com --variable SCHEME_1=http --variable SCHEME_2=https --variable PATH_PATTERN=.*

###  PhoneGap Build

```xml
<gap:plugin name="com.virtualartifacts.listeners">
  <param name="MIMETYPE_1" value="image/*" />
  <param name="MIMETYPE_2" value="video/*" />
  <param name="HOST_1" value="www.example.com" />
  <param name="HOST_2" value="example.com" />
  <param name="SCHEME_1" value="http" />
  <param name="SCHEME_2" value="https" />        
  <param name="PATH_PATTERN" value=".*" />     
</gap:plugin>
```

## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


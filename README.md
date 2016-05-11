# AdobeColorPicker
This is a rebuilt color picker for Adobe scripting.  
Supporting all Adobe softwares such as PS,AI,AE and so on.  

![AE](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/Animation.gif)

## Installation
Download the latest release.  
You can import ColorPicker to your script in following two ways:  

#### Use include (Suggested)
To use `#include`,you should specific the path to the `colorPicker.js`  
```
#include './colorPicker.js'
```
To make production, don't miss the nice command `File->Export as binary` in ESTK

#### Copy and paste
Copy all lines in `colorPicker.js`, then paste them on the top of your code.  

## Simple as pie usage
```
var resultColor = colorPicker();
resultColor;
//The rgb Array you picked up,from [0,0,0] to [1,1,1];
```

## Tip
The 4 editable text areas have shotcut keys:  
press `↑` and `↓` to add/sub 1 , while with `Shift` to add/sub 10.

## Input a default color
>The default color is specified by `new colorPicker(defaultColor)`
The default color is to be preselected in the ColorPicker,as RGB,HEX and HSB,or [1,1,1] for the platform default.

|Option   | Type | Description|
|:--------|:----:|:----------:|
|RGB      |Array |From [0,0,0] to [1,1,1] |
|LargeRGB |Array |From [0,0,0] to [255,255,255] |
|Hex      |String|From "000000" to "FFFFFF" |
|ShortHex |String|"F7C" which means "FF77CC" |
|HSB      |Array |From [0,0,0,"hsb"] to [360,100,100,"hsb"]|

## Screenshot
#### PS
>[PS](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/PS.png)  

#### AI
>[AI](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/AI.png)

#### AE
>[AE](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/AE.png)

#### ESTK
>[ESTK](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/ESTK.png)

## Changelog
#### v1.4
- Get the point from colour & Reset the position of cursor
- Much smoother moving with mouse pressed
- Support RGB, Hex and HSB in constructor
- Add support for short hex in hex field

#### v1.3
- ACP runs much faster than before
- Reduce 90% file size
- Fix invalid hex causing crash

#### v1.2
- No longer require the key-word 'new'
- Add cursor
- Better brightness control
- Auto-highlights hex field on launch
- Doesn't affect user's 'old colour' at all

#### v1.1
- Reduce 33% size of colorPicker
- Enable process for mouse-move when left mouse is pressed

#### v1.0
- First release
- Add support for all Adobe softwares 
- Add support for ESTK

#### v0.9
- Add support for Adobe AfterEffects

## Contributor
[smallpath](https://github.com/Smallpath)  
[zlovatt](https://github.com/zlovatt)

## Contribution
If you find a bug or want to contribute to the color picker,please submit an issue or send a pull request

## License
The MIT license





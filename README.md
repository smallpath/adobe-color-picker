# AdobeColorPicker
This is a rebuilt color picker for Adobe scripting.  
Supporting all Adobe softwares such as PS,AI,AE,PR and so on.  

![AE](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/AE.png)

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
Copy all lines in `colorPicker.js`, then paste it on the top of your code.  

## Usage
The key-word `new` is required to get an instance of colorPicker.  
```
var colorArr = [0.5,0.5,0.5];
var resultColorArr = new colorPicker(colorArr);  
resultColorArr;
//[0.6,1.0,0.6078431372549]
colorArr;
//[0.6,1.0,0.6078431372549]
```

## Options
- Options are specified by `new colorPicker(colorArr)`

|Parameter | Type |Default| Description|
|---------:|:----:|:-----:|:----------:|
|colorArr  |Array |[0,0,0]|The default color of colorPicker.From [0,0,0] to [1,1,1] |

## Screenshot
#### PS
>[PS](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/PS.png)  

#### AI
>[AI](https://raw.githubusercontent.com/Smallpath/AdobeColorPicker/master/_screenshot/AI.png)

See all screenshots [here](https://github.com/Smallpath/AdobeColorPicker/tree/master/_screenshot)

## Changelog
#### v1.0
- First release
- Add support for all Adobe softwares 
- Add support for ESTK

#### v0.9
- Add support for Adobe AfterEffects

## Contribution
If you find a bug or want to contribute to the color picker,please submit an issue or a pull request





# AdobeColorPicker
This is a rebuilt color picker for Adobe scripting.  
Supporting all Adobe softwares such as PS,AI,AE and so on.  

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
Copy all lines in `colorPicker.js`, then paste them on the top of your code.  

## Usage
The key-word `new` is required to get the color from an instance of colorPicker.  

#### Simple as pie usage
Just pick up a color.  

```
var resultColor = new colorPicker();
resultColor;
//The rgb Array you picked up,from [0,0,0] to [1,1,1];
```

#### Input a color usage
If you input a color,ColorPicker will not only return the color you picked up,but also change the origin color.    

```
var color = [0.5,0.5,0.5];
var resultColor = new colorPicker(color);  
resultColor;
//The rgb Array you picked up,from [0,0,0] to [1,1,1];
color;
//The value of origin color has been changed to the result color;
```

## Tip
The 4 editable text areas have shotcut keys:  
press `↑` and `↓` to add/sub 1 , while with `Shift` to add/sub 10.

## Option
- Option is specified by `new colorPicker(colorArr)`  

|Parameter | Type |Default| Description|
|:---------|:----:|:-----:|:----------:|
|colorArr  |Array |[0,0,0]|The default color of colorPicker.Range from [0,0,0] to [1,1,1] |

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
#### v1.1
- Reduce 33% size of colorPicker
- Enable process for mouse-move when left mouse is pressed

#### v1.0
- First release
- Add support for all Adobe softwares 
- Add support for ESTK

#### v0.9
- Add support for Adobe AfterEffects

## Contribution
If you find a bug or want to contribute to the color picker,please submit an issue or send a pull request

## License
The MIT license





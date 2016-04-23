# AdobeColorPicker
The rebuilt color picker of Adobe scripting for PS,AI,AE and so on.

## Demo
```
thisColor=[0.5,0.5,0.5];
colorPicker (thisColor);
```

## Options
```
colorPicker.options({
  rememberLocation: true 
})
```

#### rememberLocation
Default : true  
Decide whether the color picker should remember its location.
If true, color picker will move to the last location when it is called.

# Oxford Blue Theme

If you would like to support my work

<a href="https://www.buymeacoffee.com/blueteafrog" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

### Inspired By

The great themes in the marketplace

### Usage

**After installing the theme through the Marketplace**

Method 1. Switch between Light & Dark Mode by quick tapping <kbd>t</kbd> <kbd>t</kbd> on your keyboard
Method 2. From the settings menu select the theme and your preferred version (Light or Dark).

**Admonitions** - You can use the built in feature to invoke the different admonitions by using <kbd> < </kbd> you can find example usage at the following link https://user-images.githubusercontent.com/7694090/147600668-9adfacca-1a56-4216-a4b2-65b159ad7351.mov

**Changing Font** If you would like to use the font in the screencaps, "Montserrat" `@import` is included in the `oxford-blue.css` to use add the following to your custom.css file

```
:root {
	--ls-font-family: Montserrat;
}
```

### Screen Caps

<img src="https://user-images.githubusercontent.com/7694090/147431063-036b96cd-1e88-4f01-b80d-0f8bc0bcdcd4.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147431071-94dbe39b-6129-46ef-8fb2-ae706177972e.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147431074-13705ab5-36ed-4243-b0bc-d42f44b78471.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147431080-698e7a17-eabf-4343-afce-924e08718216.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147431121-6c27be93-57b1-4caf-acc3-0ed563b91093.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147431132-766abf74-9285-4d8b-9445-d4e55ed74b02.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147431181-bd7fd512-6e57-4dda-ad22-79743839b867.png" alt="drawing" width="200"/>
<img src="https://user-images.githubusercontent.com/7694090/147432153-7688857a-6828-4e8d-8e3d-58f991c3d2ae.png" alt="drawing" width="200"/>

### Issues & Feedback

If you experience any issues please visit the theme's repo and file an issue report. Please include a brief description and screenshot in your submission.

https://github.com/blueteafrog/logseq-oxfordblue-theme/issues

### Contributions

Contributions and suggestions to improve the theme are welcome!

### Credits

Canniblox for their clever active path and active block css shared in the discussion boards and on discord.

``` css

/*==================================================*/
/* === highlight current path by cannnibalox v0.2 ===*/
/*==================================================*/

.ls-block .bullet{
    background-color:#dd0707;
}

.ls-block:not(:focus-within) .bullet{
    background-color:var(--ls-block-bullet-color);
}

```

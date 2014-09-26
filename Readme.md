##Slider Content

Slider Content is a jQuery Plugin that shows the left and right content once the user started hovering from the image. This task was built to make sure that process style was the same from the Windows 8 Desktop version. 

###Installation

1. Start with the javascript files:
```
    <script src="js/jquery-1.11.1.js" type="text/javascript"></script>
    <script src="js/SlideRightContainer.js" type="text/javascript"></script>
```

2. Add the following code:

```
$(document).ready(function () {
    $("#slideTough").ShowLeftContent({
        datawidth : 333,
    });
});
```

This is for the sliding starting from the left.

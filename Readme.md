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

3. Add this code to the <body>

```
<div class="box-1">
    <div class="insider_box">
        <ul class="box-2" id="slideTough">
            <li><img src="images/5.png" height="166" width="333" alt="" /></li>
            <li><img src="images/6.jpg" height="166" width="333" alt="" /></li>
        </ul>
        <div class="clear"></div>
    </div><!-- End of insider_box -->
</div><!-- box-1 -->
```
***Note:*** If you want to change the height and width of the images. You need to change the parent class. From the example above, the box-1 class is the parent class.

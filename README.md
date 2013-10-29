StarlingFontAwesome
===================

A class to use the [FontAwesome](http://fortawesome.github.io/Font-Awesome/) icons in [Starling Framework](http://gamua.com/starling/).

How To Use
----------

1. set the correct package and path to the font file
2. create the object
    `protected var awe:FontAwesome = new FontAwesome(38, Color.YELLOW); // size and color (then you can change em)`  
3. you can get the image to eventually put in a [Feathers](http://wiki.starling-framework.org/feathers/start) button like this
    `var image:Image = awe.getIconImage(FontAwesome.ambulance); //any icon you want`  
    `var bt:Button = new Button();`  
    `bt.defaultIcon = image;`
4. you can get the textField to to do what you want with it
    `var textField:TextField = awe.getIconTextField(FontAwesome.linux);`  
    `addChild(textField);`  

To DO
-----
Set a cache so that if the icon is used more than once it will not be regenerated.



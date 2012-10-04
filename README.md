# rotate3Di

Zachary Johnson  
<http://www.zachstronaut.com>

Rotate3Di is a jQuery Effect Plugin that makes it possible to do an isometric 3D flip or 3D rotation of any HTML content. It also enables custom 3D rotation animations. CSS3 Transforms are used to create this visual "3D" isometric effect. Supported browsers are Safari/Chrome/Webkit, Firefox 3.5+, IE 9+, and Opera 11+. The plugin's functionality includes: setting or animating HTML content to an arbitrary isometric rotation angle, as well as flipping, unflipping, or toggling the flip state of an object.  Currently tested with jQuery 1.3.x through 1.6.

## Donate to Support this Project

Rotate3Di is, and will always be, a free plugin.  I do spend quite a bit of time answering an increasing number of emails about this project, testing it, and patching bugs.  I'd like to be able to add features and work on supporting other browsers, but I work for myself so I can't always find the time.  Consider buying me a beer, so that I can happily put more time into this project. Follow the link and click the PayPal donate button. Thank you!

<http://www.zachstronaut.com/projects/rotate3di/#donate>


           _.............._
         ,'                `.
         |`-==============-'|
        /                    \
        \     _ _ _ _ _ _    /
         |,-'            `-.| <-- Here's where I'd like my beer level to be.
         |`-._ _ _ _ _ _ .-'|
         |                  |
         |                  |
         |   ____________   |
         |,-'            `-.| <-- Here's where my beer level currently is.
         |`-.____________.-'|
    hjw  |.  ' :    .   : . |
         \  .    :   .:     /
          `._:_____:____'_.'


For more project information, code examples, and documentation visit:  
<http://www.zachstronaut.com/projects/rotate3di/>

This code is currently available for use in all personal or commercial projects under both MIT and GPL licenses, just like jQuery.

## Change Log

2012.10.04 - v0.9.2: Mainly a fix for Firefox 16, but... $(el).transform() fetches style string for current transform, which in some browsers is a matrix() statement instead of a set of separate transform functions.  This made it so I couldn't simply grep for skewY().  I was already tracking the current degrees of animation via $(el).data() anyway... so now I just return that rather than parsing from style string.  In future would be good to actually support transforms already set on an element by other code/CSS.

2012.07.24 - v0.9.1: Firefox 14 / W3C transforms change... skew() replaced with skewY()

2010.11.26 - Added to GitHub, including updated dependencies to enabled IE9 (Platform Preview 7+) support

2009.03.11 - First release of project as rotate3Di v0.9


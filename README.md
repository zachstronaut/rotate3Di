# rotate3Di

Zachary Johnson  
<http://www.zachstronaut.com>

Rotate3Di is a jQuery Effect Plugin that makes it possible to do an isometric 3D flip or 3D rotation of any HTML content. It also enables custom 3D rotation animations. CSS3 Transforms are used to create this visual "3D" isometric effect. Supported browsers are Safari/Chrome/Webkit, Firefox 3.5+, IE 9+, and Opera 11+. The plugin's functionality includes: setting or animating HTML content to an arbitrary isometric rotation angle, as well as flipping, unflipping, or toggling the flip state of an object.  Currently tested with jQuery 1.3.x through 1.6.

## Donate to Support this Project

Rotate3Di is, and will always be, a free plugin.  I do spend quite a bit of time answering an increasing number of emails about this project, testing it, and patching bugs.  I'd like to be able to add features and work on supporting other browsers, but I work for myself so I can't always find the time.  Consider buying me a beer through this PayPal donate button, so that I can happily put more time into this project. Thank you!

<form action="https://www.paypal.com/cgi-bin/webscr" method="post"><!-- You can also donate on this page: http://www.zachstronaut.com/projects/rotate3di/ --><input type="hidden" name="cmd" value="_s-xclick"><input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
"><input type="image" src="https://www.paypalobjects.com/WEBSCR-640-20110429-1/en_US/i/btn/btn_donate_SM.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!"><img alt="" border="0" src="https://www.paypalobjects.com/WEBSCR-640-20110429-1/en_US/i/scr/pixel.gif" width="1" height="1"></form>


           _.........._
         ,'            `.
         |`-==========-'|
        /                \
        \     _ _ _ _    /
         |,-'        `-.| <-- Here's where I'd like my beer level to be.
         |`-._ _ _ _ .-'|
         |              |
         |              |
         |   ________   |
         |,-'        `-.| <-- Here's where my beer level currently is.
         |`-.________.-'|
    hjw  |.  ' :    : . |
         \  .    :      /
          `._:______'_.'


For more project information, code examples, and documentation visit:  
<http://www.zachstronaut.com/projects/rotate3di/>

This code is currently available for use in all personal or commercial projects under both MIT and GPL licenses, just like jQuery.

## Change Log

2010.11.26 - Added to GitHub, including updated dependencies to enabled IE9 (Platform Preview 7+) support

2009.03.11 - First release of project as rotate3Di v0.9


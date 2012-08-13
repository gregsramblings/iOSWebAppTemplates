Creating iOS web apps can be very error prone.  The size requirements for icons and splash screens are odd
and there are a few things that are non-obvious (e.g. the iPad landscape splash image is actually a portrait-shaped
image but has it's contents rotated; Retina displays reserve 40 pixels for the status bar while non-retina reserve 20 pixels, etc.).  
Also, if you screw something up, you get no errors.  It just simply doesn't work leaving you to guess/hack.

What started as a 15 minute attempt to get icons and splash screens working for my web app resulted in a couple of hours
of what felt like pure hacking.  Many of the online resources (including Apple's!) were out of date and didn't include
information on handling iPad retina icons/images.

The webapp1 template is a simple web app that has icons and splash screens that have been tested on an iPhone 3Gs, 
iPhone 4, iPhone 4s, iPad 1, iPad 2, and the "new iPad (retina).

Few fun facts:
<ul>
<li>iPhones don't need a landscape splash screen.  The apps always display a portrait splash image regardless of orientation.  
The app itself will turn landscape as expected, but it always launches as portrait.
<li>The iPad landscape splash screen is a weird thing -- it's actually a portrait-shaped image with rotated content.  
</ul>

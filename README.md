# WolfChart v1.7
by Ballantyne de Wolf and Offspring Digital

This is professional optometrist/optician/ophthalmologist tool for measuring visual acuity. It cannot be used safely by the general public.
If you have any concerns about your vision or eyes, consult a qualified professional.

Now that's out of the way, the objectives are:
  1. Clinically relevant, scientifically supported visual acuity measurement in the widest possible range of clinical and research settings
  2. Open source with GNU licence
  3. Can be used on a wide variety of screen hardware
  3. Customisable optotypes and alphabets to come eg Hebrew, Chinese, Thai, Cyrillic etc
    
    
Ver1.7
 - added colour picker for background that defaults to white. This is maybe only useful in a research environment.
 - added Vanishing Sloan optotype/Vanishing ETDRS alphabet.When selected, body background colour is same as optotype colour but 0.5 opacity. Used jquery.not() to exempt white filled elements from optotype color. Body bg reverts to stored with all other optotypes.
 - Added prototype Shapes optotype
 - Set color of scoreBox text to be optotype color with opacity 1, so that it will always be the same or more visible than the optotype itself.
 - thinking of replacing all the fills in the svg raw materials section with classes and then using jquery to fill. Could be more flexible that way?
 - simplified css in .duo to try and eliminate white gaps in duochrome backgrounds.

Ver1.6
 - subtense array now to 3 decimal places, enabling
 - improved scoring for Actual Numerators - fractional notations are rounded to 0.1m or 0.5ft and the / is replaced by a ! when Actual is selected.
 - cleaned up some superfluous code lines in this area.
 - updated help topics
 - changed the Snellen R to try and make it more readable - in the field it was proving less readable than the other Snellens. Made the oblique stem more vertical.

Ver1.5
 - PWA version
 - new alphabet for Snellen BS4274.3 - less random

Ver1.4
 - various bug fixes
 - improved consistency of svg elements to use only filled paths and polygons, no strokes.
 - improved implementation of rgba to permit overlapping elements - opacity is now applied to the whole svg element, not its child elements
 - larger, more readable VA labels
 - shortcut keys validated as unique
 - scoreBox label element click/tap masks that line


Ver1.3
Added duochrome function with a shortcut key to be assigned in config form.
Help and very quick guide updated

Ver1.2
Help text updated

Expanded Sloan and Snellen optotypes.

New alphabets for 
  - BS4724.3
  - SnellenU
  - ETDRS
  - SloanU

Improved letter R in both Sloan and Snellen
  - ISSUE need to apply opacity to svg, not elements of svg, so that characters can have overlapping elements

Added text under HELP in guide-section:  "Very quick guide: Calibrate and configure your chart using this help guide. Click or tap on white space to scroll the chart up and down, or use the up and down arrows on your keyboard. Click or tap on any letter to mask it. Click it again to unmask."

Ver1.1
Supports 4 optotypes with an alphabet each. Help text needs some work.

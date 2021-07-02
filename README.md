# WolfChart v2.3
by Ballantyne de Wolf, Offspring Digital

This is professional optometrist/optician/ophthalmologist tool for sight testing. It cannot be used safely by the general public.
If you have any concerns about your vision or eyes, consult a qualified professional.

Now that's out of the way, the objectives are:
  1. Clinically relevant, scientifically supported sight testing tools, in the widest possible range of clinical and research settings.
  2. Open source with GNU licence
  3. Can be used on a wide variety of screen hardware
  3. Customisable optotypes and alphabets to come eg Arabic, Hebrew, Chinese, Thai, Cyrillic etc

Ver2.3
  - Bug fixes
    - guide dots on V charts hide and show behaviour fixed
    - shuffle and duochrome disabled in single and column modes
    - 
  - Additions
    - Experimental optotypes in Chinese, Arabic and Hebrew
    - Removed the Man from Shapes5, leaving 5 shapes in use, and set out alphabet to work better vertically

Ver2.2
  - Bug fixes
    - moved SVG transforms to css transforms. Safari doesn't implement SVG transform, all browsers implement SVG.css transform. Means have to add units
    - fixed badly-written rotate90 function, also not working on Safari
    - Rejigged Snellen BS4724 6/6 and 6/5 lines to get rid of an FU
    - fixed sidebar controls not responding to nav links
    - fixed text-decoration in nav-button-div a
  - Additions
    - characterClick now cycles through: mask one letter > mask column of letters > show all >

    

Ver2.1
 - Now displays charts in 4 categories, using direction buttons and keys to navigate
 - Paging up and down the letter chart now done by showing and hiding fullscreen pages, rather than scrolling a larger-than-fullscreen page
 - Right hand sidebar containing controls
 - Chart keeps track of your usage, offering your most-used chart on key strokes and nav buttons
 - Fixed viewport - now uses document.documentwindow.clientHeight and a trimmed window.innerWidth at all times
 - Single charts have spacebar/onclick/button function to eg zoom
 - Removed colour pickers, replaced with text, preset buttons and hue-only sliders for filter tests
 - Various improvements under bonnet
 - Switched off PWA features like manifest and sw.js - will maybe bring them back later.
 - Versioned as X.y in localStorage
    
Ver1.8
 - fixed bug of bg colour not stored on first use.
 - added coloured dots at 6/4.8(20/16,-0.1,1.1, normal VA) and 6/12(20/40,0.3,0.5, legal VA).
 - did some code cleaning
 
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

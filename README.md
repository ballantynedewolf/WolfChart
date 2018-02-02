# WolfChart v1.4
by Ballantyne de Wolf and Offspring Digital

This is a professional optometrist/optician/ophthalmologist tool for measuring visual acuity. It cannot be used safely by the general public.
If you have any concerns about your vision or eyes, consult a qualified professional.

Now that's out of the way, the objectives are:
  1. Clinically relevant, scientifically supported visual acuity measurement in the widest possible range of clinical settings
  2. Open source with GNU licence
  3. Can be used on a wide variety of screen hardware
  3. Customisable optotypes and alphabets to come in version 2

# How to use WolfChart without an internet connection
As WolfChart is 100% Javascript, once it is open in your browser, no internet connection is needed. You will need to turn off any script blocking for WolfChart and do not prevent it from using Local Storage.
 - Extract this archive to a location on your computer or network where it is unlikely to get moved in a hurry.
 - Drag the **index.htm** file from this archive into your browser or paste its path into the browser address bar or use the browser's File>Open File menu option to search for it.
 - Use the menu button top right to configure and calibrate your chart as normal
 - Might be a good idea to bookmark it so that you can return quickly to WolfChart. Your configuration and calibration settings are kept even when you close the browser.
 - Check periodically for updates when you have an internet connection. The version you are using is in the page title.

# Version notes    
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

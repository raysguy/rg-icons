# gg-icons
### *by guygamer*
**Crisp and sharp icon font for torrent/nzb clients and providers designed by @guygamer.**

Originally designed as torrent/nzb client and provider icons for the HTPC Manager project but I'm making them available here as they could be useful to other projects.  I was frustrated with how poor png graphics look when used as icons and using svg files was proving problematic.  So I decided to create my own set of icons as an icon font that would look crisp and sharp at all sizes (including Retina displays) and could be easily manipulated.  I tried to create simple and clear icons that would be easily recognisable at any size whilst also capturing the spirit of the original client and provider logos.  I anticipate adding more icons in the future on an as-needed basis.

###How to use
Just follow these simple steps:
 1. Download the latest release from [here](https://github.com/guygamer/gg-icons/releases/latest)
 2. Extract the files and copy to your project
 3. Ensure the CSS is correctly referenced
 4. Include the icons by using the "rg" class followed by the icon name: `<i class="gg gg-logo"></i>`
 5. Manipulate the icon as you would any other font, ex: `<i class="gg gg-logo" style="font-family:'gg-icons';font-size:28px;font-weight: normal;color:#00ff00"></i>`

To see a full list of included icons along with the correct icon name to use please see the `gg-icons-demo.html` file included in the root of the rg-icons source.
 
###Special classes
You can use some special classes I created to quickly customise any rg-icon.  Just include these modifiers to the class:
 * `gg-xs` - 16px size - ideal for buttons and icons, ex: `<i class="gg gg-logo gg-xs"></i>`
 * `gg-inverse` - inverted icon - ideal if using rg-icons on a dark background, ex: `<i class="gg gg-logo gg-inverse"></i>`
 * `gg-[name]-c` - coloured icon - use a brand-coloured version of an icon by appending `-c` to the name, ex: `<i class="gg gg-logo-c"></i>`
 
###Requests
If you're using gg-icons in your project and want an icon for any software/service that isn't included feel free to open an issue and make a request.  I'll try to get round to these if and when I get chance.  gg-icons is a project I work on in my free time and sometimes life gets busy so no guarantees.

Please start the title of any request with [REQUEST] and include an image of the logo it is to be based on in the request itself (this is easy to do on github!).

*NB - Please only request icons for known software and services.  No requests for personal designs and nothing of a lewd or adult nature.*

###Version History
 * v1.5.0 2016-02-07
  - Added icon for torrentproject (by request)
  - Backend changes to remove CSS font embedding

 * v1.4.0 2015-06-19
  - Added icon for rarbg (by request)

 * v1.3.0 2015-06-10
  - Added icon for passthepopcorn (by request)
  - gg-icons site added [http://guygamer.github.io/gg-icons](http://guygamer.github.io/gg-icons)
 
 * v1.2.0 2015-04-28
  - Added gg-icons logo
  - Added two alternative icons for Plex
  - Added brand-coloured style for icons: append `-c` to an icon name to activate
  - Updated gg-icons demo to reflect latest changes and show colour options
  - Dropped support for versions of IE lower than IE8

 * v1.1.0 2015-04-26
  - Initial public release

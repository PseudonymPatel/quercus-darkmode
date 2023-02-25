# webassign-darkmode
My take on a darkmode for the student service Quercus (which is an instance of Canvas)

# Installation
Installation is real simple!
1. Install Stylus for either Firefox, Chrome or Opera or Cascadea for Safari.
2. Go to [this](https://raw.githubusercontent.com/PseudonymPatel/quercus-darkmode/master/quercus-darkmode.user.css)  page and a thing should come up asking to install the stylesheet. 
3. Configure and install
4. In the extension, there are customization options. You can change things like the text colors, background colors, etc. 
5. Style updates should be automatic or you can go to the extension to check for updates.

# Helping out
1. Install the stylesheet first
2. Go into the stylesheet extension to edit it through the extension's editor. 
3. Fork and pull request.

### KEEP IN MIND WHEN WORKING ON THIS:
- I use the [less preprocessor](http://lesscss.org/) to allow for a more dynamic/customizable ui.
- Do not use the css-asdfla tags, they are machine generated and might change.  
- Use as few tags as possible and make it as generic as you can, when possible. (ie. don't do each of the assignment, calendar cards individually, do them all at once using one css selector)  
- Try to avoid using !important when possible, it can break things, and there is 99% a better way (hint: be more specific in the selector)

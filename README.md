http://step-1xx.iambeardednbroke.com/index.html

Step 1xx

inside out project version 100-0

	- added header resize functionality

inside out project version 100-1

	- added footer resize functionality
	- added jQuery, tether, popper# Step-1xx

inside out project version 100-2

	- fixed the footer by adjusting bootstrap column widths wrapping them inside a bootstrap row
	
inside out project version 101-1

	- added first level of navigation
	- created assets/js/app.js
	- created assets/data/menu.json
	- moved header-resize js to app.js
	
inside out project version 102-1

	- completed menuBUilder function in app.js
	- completed nav through menuBuilder function with recursion
	
inside out project version 102-1

	- completed css for navigation
	
inside out project version 103-0

	- fixed enlarging navigation on header shrink
	- added loader to application with gears
	
inside out project version 104-0

	- modified the ajax call to get the JSON for the menu from the me.beardednbroke.com site
	- modfied the menuBuilder function to accept the JSON data from WordPress REST API
	- removed data/menu.json from file system considering it is no longer needed
	
inside out project version 105.0 README.md file changes - prepended the title to the production site link - added link to GitHub Pages to the top of the content me WP Site Changes - added and activated a new theme - WP Bootstrap Starter - Version: 3.0.11 - By Afterimage Designs - added home page name "iop-html5 - home" to pages do not add to menu - added content https://www.diffchecker.com/3ZeHoYyZ - nest all pages below your home page "iop-html5 - home" - updated "Main Menu" to "iop-html5 Menu"

 inside out App Site Changes
 
 - index.html
 
      - removed comments and cleaned code
      - added the click event to the logo - calls the getPage function
      - removed both main content sections
      - added the circle loading div and content
	  
 - style.css
 
      - added the logo & logo:hover classes for the logo in the header - no inked
      - added the section class to keep the page from closing all the way when there is no content
      - added the following classes for the loader circle 
           - circle, wave, wave:before, wave:after
           - add keyframes for animation animate
		   
 - app.js
 
      - removed comments and cleaned code
      - added the getPage function to capture link clicks and get page content
      - added getPage function call to the ajax call for the menus on page load to get the homepage
      - modified the forEach loop in the menuBuilder to include the page id as a data attribute
	 
  inside out project version 106.0
  
     me WP Site Changes
     - add the pages for the links in the general links section in the footer
        - contact us, frequently ask questions, terms & conditions, privacy policy
     
     inside out App Site Changes
     - index.html
          - add id="genLinks" to the ul in the "General Links" section in the footer
     - app.js
          - add ajax call to gret the general links menu
          - add variables to the menubuilder function to accepet id and class information   
Fonticons
=========

A collection of open web icon fonts

To use, simply:

*   Import the icon fonts(s) into your css and add the font-family('s):

		@import url(https://raw.github.com/mikestecker/fonticons/master/application.js);

		/* Brandico.font */
		[class*="brandico-"]:before {
			font-family: 'brandico', sans-serif;
		}
		/* Entypo */
		[class*="entypo-"]:before {
			font-family: 'entypo', sans-serif;
		}
		/* FontAwesome */
		[class*="fontawesome-"]:before {
			font-family: 'FontAwesome', sans-serif;
		}
		/* OpenWeb Icons */
		[class*="zocial-"]:before {
			font-family: 'OpenWeb Icons', sans-serif;
		}
		/* zocial */
		[class*="zocial-"]:before {
			font-family: 'zocial', sans-serif;
		}

*   Burn baby, burn!

		<!-- Single Element -->
		<span class="zocial-dribbble"></span>
    	    
		<!-- Group of Elements -->
		<ul>
			<li class="zocial-twitter"></li>
			<li class="zocial-appstore"></li>
			<li class="zocial-flickr"></li>
			<li class="zocial-lastfm"></li>
			<li class="zocial-meetup"></li>
			<li class="zocial-reddit"></li>
		</ul>
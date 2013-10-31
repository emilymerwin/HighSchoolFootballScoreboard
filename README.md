#Highschool Football Scoreboard
- Rebuilt for 2013 season with HTML/jQuery/d3 to replace old flash version
- Live <a href="http://www.ajc.com/high-school-football-scoreboard/" taret="_blank">here</a>
- Currently not compatible with IE 8 or older due to CORS and d3 support. Might be able to fix for IE 8 but CORS won't work for anything older

###Dependencies
- <a href="https://github.com/MoonScript/jQuery-ajaxTransport-XDomainRequest" target="_blank">XDomainRequest</a> plugin to support CORS in IE 9, should work for IE8 also, but it was choking on d3, maybe need to try <a href="https://github.com/jquery/sizzle" target="_blank">Sizzle</a> to support selectors
- <a href="https://github.com/GumbyFramework/Gumby" target="_blank">Gumby</a> CSS framework for grid system
	* Gumby uses <a href="http://modernizr.com/" target="_blank">Modernizr</a> for a bunch of stuff like optimizing for touch devices, choosing image resolutions etc.
- jQuery UI primarily for the autocomplete feature
- d3 because of all the adding/removing things from the DOM, but might be better to just use jQuery, which would work with IE 8

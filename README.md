#High School Football Scoreboard
- Rebuilt for 2013 season with HTML/jQuery/d3 to replace old flash version
- Live <a href="http://www.ajc.com/high-school-football-scoreboard/" taret="_blank">here</a>
- Uses <a href="https://github.com/MoonScript/jQuery-ajaxTransport-XDomainRequest" target="_blank">XDomainRequest</a> plugin to support CORS in IE9, should work for IE8 also, it was choking on D3, maybe need to try <a href="https://github.com/jquery/sizzle" target="_blank">Sizzle</a> to support selectors, app does not use SVG
- Currently not compatible with IE 8 or older due to CORS and d3 support. Might be able to fix for IE 8 but CORS won't work for anything older

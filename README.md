# learningReact
for any small projects/tutorials while practicing react

## Basic Tools:
### HTML
Backbone of all websites. Structures data. Annotates site text. Dictates site architecture. Dictates text display.
  - uses tags (descriptive commands) which indicate to browser that the text in the brackets needs to be processed.  
  ex: \<b>bold\</b> will produce <b>bold</b>
  - *procedural markup:* instructions to browser on how to display text. information for browser to interpret 
  - *descriptive markup:* labels for documentation.  
  
**XML**: Extensible Markup Language
 - describes elements of data (nodes) but doesn't display data
 - major building block of AJAX --> XMLHTTPRequest is key to AJAX 
 
**XHTML**: Extensible HyperText Markup Language
  - HTML4 + elements of XML
  - stricter language than HTML, tougher to debug
  - same format as XML app
  - made obsolete by HTML5
  
**HTML5**: 
  - hybrid of HTML, CSS, JavaScript
  - agile architecture, mobile-friendly, compatible with most browsers
  - cross-platform app dev
  - new APIs and features <-- no need for 3rd party

### JavaScript
How the page is made interactive.

**Frameworks**
- AngularJS
- React

**JQuery**
- JS object library
- ensures that JS runs exactly the same on every browser
- concise, reusable JS bundles
- responses are *event-based*
  - user interaction = event
  - *selectors* find and modify HTML elements with using CSS
- to use: 
  - reference CDN (content delivery networks) link in <script> tag
  - register a ready event for the document 

**Task Runner Tools**
workflow management tools. tackle repetitive but essential tasks. programs with plug-ins
- Grunt
- Glup

### CSS
how elements appear. background colors. navigation bars. fonts and text alignment.
- works with HTML but kept in a separate file -- changes in appearance don't affect structure
- cascading --> globally update design for multiple pages at once -- streamlined to one layered file

**CSS3**: 
- backwards-compatible with older versions of CSS
- debugs and extends past features
- mobile development, accounts for responsive design -- handle media quaeries 
- Flash functionality by working with JavaScript
- split into modules: selectors, box model, backgrounds, borders, text effects
- web font support (google font/typecast), use more than web safe fonts
- faster dev and faster load times 
- transformations, animations, transitions without JS or Flash
- new colors/gradient colors and image effects 
- box-sizing addressing alignment problems 
  
**CSS Grid**
- doesn't require a framework, just browser compatibility
- new layout control, works with existing layout tools
- easier to build dynamic, asymmetrical layouts - control of both col and rows simultaneously 

**Sass**:
- CSS pre-processor, code in Sass and it will be compiled into a CSS file
- variables: reduces repetitive work, don't have to code in-line 
- mixin: group CSS declarations and reuse them throughout the file 
- responsive design: "respond-to" mixin `that make it easier to write media queries and create responsive breakpoints
- partials: code snippets, don't get compiled into CSS
- extenders: shared attributes are coded once and inherited 
- nesting: hierarchy 
- uses Ruby scripting language 
- frameworks --> Compass, Bourbon

**Frameworks**:
- Bootstrap
- Foundation

### AJAX
Asynchronous JavaScript + XML. asynchronously exchange small amounts of data with the server behind the scences without affecting the rest of the page
- ex: drop-down menus, predictive text, auto-fill
- less stress on the network and faster operations 
- asynchronous: behind the scenes, independent from each other 
- breakdown:
  - XML/JSON
  - CSS
  - JavaScript
  - XMLHttpRequest objects: retrieve the data with the server behind the scenes
- callbacks vs. postbacks:
  - pre-AJAX: any browser request from db makes a site responsive, Postbacks 
  - post-AJAX: request small amounts of data directly from the server, no need for postback, Callback
- benefit of AJAX:
  - better speed and performance
  - more responsive, user-friendly
  - browser-/platform-independent
  - ideal for updating small bits of info
  - won't slow down with limited bandwidth

**JSON**:
- data interchange format, improve server-to-browser communications
- text only, uses brackets and tags
- written in JavaScript format, compatible with front-end, JSON can be directly converted into JS 
- doesn’t require an end tag, won’t “break” without one
- shorter to read and quicker to write
- uses arrays
- makes AJAX faster


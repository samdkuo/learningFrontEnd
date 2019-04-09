# learningReact
for any small projects/tutorials to help me practice react
websites: 

## Basic Tools:
### Markup Languages
Backbone of all websites. Structures data. Annotates site text. Dictates site architecture. Dictates text display.
  - uses tags (descriptive commands) which indicate to browser that the text in the brackets needs to be processed.  
  ex: \<b>bold\</b> will produce <b>bold</b>
  - *procedural markup:* instructions to browser on how to display text. information for browser to interpret 
  - *descriptive markup:* labels for documentation.  
  
**HTML**: HyperText Markup Language
  - descriptive markup lanuage
  - tells browser how to process and display text
  
**XML**: Extensible Markup Language
 - describes elements of data (nodes) but doesn't display data
 - major building block of AJAX --> XMLHTTPRequest is key to AJAX 
 
**XHTML**: Extensible HyperText Markup Language
  - HTML4 + elemnts of XML
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
- doesn't require a framework, just browser compatiblity
- new layout control, works with existing layout tools
- easier to build dynamic, asymmetrical layouts - control of both col and rows simultaneously 

**Sass**:
- CSS pre-processor, code in Sass and it will be compliled into a CSS file
- variables: reduces repetitive work, don't have to code in-line 
- mixin: group CSS declarations and reuse them throughout the file 
- responsive design: "respond-to" mixin that make it easier to write media queries and create responsive breakpoints
- partials: code snippets, dont get compiled into CSS
- extenders: shared attributes are coded once and inherited 
- nesting: hierarchy 
- uses Ruby scripting language 
- frameworks --> Compass, Bourbon

**Framworks**:
- Bootstrap
- Foundation

### AJAX
Dynamic applications. Independent sections in an app. 

**JSON**:

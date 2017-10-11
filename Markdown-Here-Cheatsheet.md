**Directory** - Listing Templates

Welcome to the *Directory* Listing Templates.


**Directory Template Documentation**

This document covers the installation and use of this theme and often reveals answers to common problems and issues - read this document thoroughly if you are experiencing any difficulties. If you have any questions that are beyond the scope of this document, feel free to pose them in the dedicated support section.

Should anything else be here? Add it (either here or in another page)!


**Features and Functionality**
<ol>
<li>Responsive Design</li>
<li>W3 Validation Code</li>
<li>Build on Bootstrap 3</li>
<li>Retina Ready</li>
<li>Clean & Optimized Code</li>
<li>800+ Font Icons</li>
<li>CSS3 onscroll animation</li>
<li>Fully Responsive Design</li>
<li>All files are well commented</li>
<li>browser Compatible with IE9+, Firefox, Safari, Opera, Chrom</li>
<li>Google map</li>
</ol>


Check out the **[Full Template Features](wiki/Markdown-Here-Cheatsheet)** to discover what you can do in *Markdown Here*. (There is also a [Markdown Cheatsheet](wiki/Markdown-Cheatsheet) that is not specific to *Markdown Here*.)
##### Table of Contents

[Getting started](#Getting started)  
[CSS](#CSS)  
[The JavaScript](#The JavaScript)  
[Links](#links)  
[Images](#images)  
[Code and Syntax Highlighting](#code)  
[Tables](#tables)  
[Blockquotes](#blockquotes)  
[Inline HTML](#html)  
[Horizontal Rule](#hr)  
[Line Breaks](#lines)  
[YouTube Videos](#videos) 
[Headers](#headers)  
[Emphasis](#emphasis)  
[Lists](#lists)  
[Links](#links)  
[Images](#images)  
[Code and Syntax Highlighting](#code)  
[Tables](#tables)  
[Blockquotes](#blockquotes)  
[Inline HTML](#html)  
[Horizontal Rule](#hr)  
[Line Breaks](#lines)  
[YouTube Videos](#videos)   


<a name="Getting started"/>


## Getting started
[Directory - Listing Templates](https://pixelaar.com/) | [Documentation
table of contents](TOC.md)

* [Usage](usage.md) — Overview of the project contents.
* [FAQ](faq.md) — Frequently asked questions along with their answers.

## Directory- Listing Templates

* [HTML](html.md) — Guide to the default HTML.
* [CSS](css.md) — Guide to the default CSS.
* [JavaScript](js.md) — Guide to the default JavaScript.
* [Installing template](Installing template.md) — Guide to the default JavaScript.
* [Reference link](Reference link.md) — Guide to the default JavaScript. 
## Development

* [Extending and customizing HTML5 Boilerplate](extend.md) — Going further
  with the boilerplate.

## Related projects
Tools required for students and teachers

A computer (Linux, Mac or PC will do)

One or more modern web browsers. We'd recommend that you install the latest versions of Opera, Firefox, Safari, Chrome, and Internet Explorer, depending on what is available for your OS.

An internet connection

**A text editor. The free ones we'd recommend are:**

<ol>
<li>Windows: [Notepad++]</li>
<li>Mac: [TextWrangler]</li>
<li>Linux: [BlueFish]</li>
</ol>

**An FTP client. The free ones we'd recommend are:**



<ol>
<li>Windows and Linux: [Filezilla]</li>
<li>Mac: [Cyberduck]</li>

</ol>

Additional tools required for teachers
Example files to demonstrate discussed concepts
An installed server-side testing environment, like [MAMP] or [WAMP] or [XAMPP]

<a name="CSS"/>

##CSS
We are using one primary CSS file for this template: /css/style.css. This file contains all style information for the template .

Use one of the included child themes as a base for further CSS customization.

Styles are being used and test-edit the CSS.
   
   ink rel="stylesheet" href="css/font-awesome.min.css">
   
       <!-- magnific popup css-->
       <link rel="stylesheet" href="css/magnific-popup.css">
   
       <!-- animate css -->
       <link href="css/animate.min.css" rel="stylesheet">
   
   
       <!--owl carousel -->
       <link href="owlcarousel/assets/owl.theme.default.min.css" rel="stylesheet">
       <link href="owlcarousel/assets/owl.carousel.min.css" rel="stylesheet">
   
       <!--custom scroll bar css-->
       <link rel="stylesheet" href="css/jquery.mCustomScrollbar.min.css">
   
       <!-- bootstrap core css -->
       <link href="css/bootstrap.min.css" rel="stylesheet">
   
       <!-- custom css -->
       <link href="css/style.css" rel="stylesheet">
   
       <!-- responsive css -->
       <link href="css/responsive.css" rel="stylesheet">
<a name="The JavaScript"/>

## The JavaScript

The JavaScript / jQuery plugins uses are stored in js/ folder. You do not need to edit these items.

The script(s) you can edit as needed are:

js/scripts.js - This contains the plugin setup / init and general information
    
    !-- main jQuery -->
    <script src="js/jquery-3.2.1.min.js"></script>
    
    <!-- bootstrap core js -->
    <script src="js/bootstrap.min.js"></script>
    
    <!-- wow.min.js -->
    <script src="js/wow.min.js"></script>
    
    <!-- smoothscroll -->
    <script src="js/jquery.easeScroll.js"></script>
    
    <!--owl carousel-->
    <script src="owlcarousel/owl.carousel.min.js"></script>
    
    <!--Custom Scroll Bar-->
    <script src="js/jquery.mCustomScrollbar.js"></script>
    
    <!-- scrolling nav -->
    <script src="js/jquery.easing.min.js"></script>
    
    <!--Sidenav js-->
    <script src="js/sidenav.min.js"></script>
    
    <!--animation text js -->
    <script src="js/animation-text.js"></script>
    
    <!--magnific popup js-->
    <script src="js/magnific-popup.min.js"></script>
    
    <!-- custom script -->
    <script src="js/scripts.js"></script>

## scripts.js

This file can be used to contain or reference your site/app JavaScript code.
If you're working on something more advanced you might replace this file
entirely. That's cool. 

    // ------------------------------------------------------------------
    // jQuery for back to Top
    // ------------------------------------------------------------------

    (function(){

        $('body').append('<div id="toTop"><span>Up</span></div>');

        $(window).scroll(function () {
            if ($(this).scrollTop() != 0) {
                $('#toTop').fadeIn();
            } else {
                $('#toTop').fadeOut();
            }
        });

        $('#toTop').on('click',function(){
            $("html, body").animate({ scrollTop: 0 }, 600);
            return false;
        });

    }());


## plugins.js



One approach is to put jQuery plugins inside of a `(function($){ ...
})(jQuery);` closure to make sure they're in the jQuery namespace safety
blanket. Read more about 

By default the `plugins.js` file contains a small script to avoid `console`
errors in browsers that lack a `console`. The script will make sure that, if
a console method isn't available, that method will have the value of empty
function, thus, preventing the browser from throwing an error.
##maps
This file can be used to contain all your website maps such as jQuery plugins and
other 3rd party scripts for a simple site.
 
 
     var map = new google.maps.Map(document.getElementById('map'), {
            zoom: zoomLevel,
            scrollwheel: scrollEnabled,
            center: new google.maps.LatLng(40.80, -73.70),
            mapTypeId: google.maps.MapTypeId.ROADMAP,
            zoomControl: false,
            mapTypeControl: false,
            scaleControl: false,
            panControl: false,
            navigationControl: false,
            streetViewControl: false,
            styles: [{
                "featureType": "poi",
                "elementType": "labels.text.fill",
                "stylers": [{
                    "color": "#747474"
                }, {
                    "lightness": "23"
                }]
            },
## vendor

This directory can be used to contain all 3rd party library code.

Minified versions of the latest jQuery and Modernizr libraries are included by
default. You may wish to create your own.
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~


<a name="lists"/>

## Lists

```no-highlight
1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```

1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses

<a name="links"/>

## Links

There are two ways to create links.

```no-highlight
[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

<a name="images"/>

## Images

```no-highlight
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

<a name="code"/>

## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and *Markdown Here* -- support syntax highlighting. *Markdown Here* supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the [highlight.js demo page](http://softwaremaniacs.org/media/soft/highlight/test.html).

```no-highlight
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks <code>```</code>, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

<pre lang="no-highlight"><code>```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a &lt;b&gt;tag&lt;/b&gt;.
```
</code></pre>



```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let's throw in a <b>tag</b>.
```

Again, to see what languages are available for highlighting, and how to write those language names, see the [highlight.js demo page](http://softwaremaniacs.org/media/soft/highlight/test.html).

<a name="tables"/>

## Tables

Tables aren't part of the core Markdown spec, but they are part of GFM and *Markdown Here* supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

```no-highlight
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables        | Are           | Cool |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

<a name="blockquotes"/>

## Blockquotes

```no-highlight
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 
```

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

<a name="html"/>

## Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well. 

```no-highlight
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

<a name="hr"/>

## Horizontal Rule

```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

<a name="lines"/>

## Line Breaks

My basic recommendation for learning how line breaks work is to experiment and discover -- hit &lt;Enter&gt; once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend. 

Here are some things to try out:

```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also begins a separate paragraph, but...  
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

(Technical note: *Markdown Here* uses GFM line breaks, so there's no need to use MD's two-space line breaks.)

<a name="videos"/>

## YouTube Videos

They can't be added directly but you can add an image with a link to the video like this:

```no-highlight
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```

Or, in pure Markdown, but losing the image sizing and border:

```no-highlight
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```
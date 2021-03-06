

# What is Txt2tags? 

## You may have heard about Txt2tags, if you have it's a good thing 

**Txt2tags means that your content is being created correctly... by professionals.**

In the past you may have heard of [WYSIWYG](http://en.wikipedia.org/wiki/WYSIWYG) 
(what you see is what you get) and [HTML](http://en.wikipedia.org/wiki/HTML) formatting. 
Think of Txt2tags like a simplified WYSIWYG or HTML ... simplified in the best way.

When designers and developers approach a project, they build [styles](http://www.w3schools.com/css/) 
into the project. Those styles dictate how basic elements, like headers and links, will appear. 
The styles are applied throughout the entire project.

In the past, a WYSIWYG or HTML editing tool had too much control. Someone could unknowingly 
add a new style to the design (like red italic bold headers) without meaning to. More often 
than not, it was a purposeful addition, but that leads to a *race to the bottom*, so style 
treatment became larger, bolder, and brighter. This makes designers sad :( because their 
carefully crafted theme is tossed by the wayside, like stuff... old stuff.

Bottom line, people who edit content should focus on the words and the designer should 
make them pretty. Txt2tags does an excellent job at drawing a line in the sand, equipping 
us to all play nice together. The neat part is that when a designer pushes a new style to 
your website, it is consistently reflected across the whole chalupa, so they keep the design 
fresh and stay on top of browser caveats and features. 

Txt2tags is widely accepted by [developers and editors](https://duckduckgo.com/?q=love+txt2tags), 
so it's the best choice for implementing best practice. Nearly every popular content management 
solution supports Txt2tags, if not out-of-the-box, then with an easy-to-install extension.

## Txt2tags tools for Writers 

**Anyone who works with content should be using one of the following tools...**

*Note: Most things about Txt2tags are free.*

#### Editors 

 * Any text editor can do the job. Some of them have syntax highlight or sections shortcuts, 
such as [Geany](http://geany.org/), [Kate](http://kate-editor.org/) 
or [Scite](http://www.scintilla.org/SciTEDownload.html). Advanced users might prefer 
using [Vim](http://www.vim.org/) which has the best txt2tags support.

*Find something that works better for you? No problem. Your .t2t files are small and portable,*
*and aren't locked away inside a proprietary format or hidden away inside an arcane XML file.*
*They're right there in a folder you own and control, ready to be used somewhere else if you need them.*

#### Online Tools 

 * [PmWiki](http://wiki.txt2tags.org/index.php/Main/Txt2tagsAndPmWiki)  
 * [Dokuwiki](http://www.dokuwiki.org/plugin:txt2tags)
 * [LionWiki-t2t](http://wiki.txt2tags.org/demos/lionwiki-t2t/)
 * [Wordpress](http://wiki.txt2tags.org/demos/wordpress)
 * to be continued... (drupal, jekyll etc.)

#### Others 

 * [txt2tags and php](http://txt2tags.org/txt2tags.form.php)
 * [txt2tags and javascript](http://wiki.txt2tags.org/demos/txt2tagsjs)

## How do I write this Txt2tags stuff? 

When developers talk about how to write something, they call it syntax.

To that end, here are related syntax documents sorted by ease of use.

 * [Txt2tags syntax](http://txt2tags.org/markup.html) - Formatting guide
 * [Txt2tags user guide](http://txt2tags.org/userguide/) - The original guide by the author
 * [Wikipedia](http://en.wikipedia.org/wiki/Txt2tags) - History and formatting guide

## About 

[Txt2tags](http://www.txt2tags.org/) is made by [Aurelio Jargas](http://aurelio.net/), 
and [a team of several people](http://www.txt2tags.org/team/). 

Txt2tags is a document generator and a lightweight markup.

It reads a text file with minimal markup such as **bold** and *italic*. Its python implementation 
can convert to several formats such as html, docbook, LaTeX, RTF, Man page, Creole, Wikipedia / 
MediaWiki, PmWiki, DokuWiki, MoinMoin, AsciiDoc...

It is very extensible and customisable, by using regex and preprocessors.

Its php implementation targets only HTML but you can use it with several CMS, Blog and wiki 
engines: Wordpress, Drupal, Dotclear, Dokuwiki, LionWiki... 

## I still don't understand 

Txt2tags can be written in a basic text editor (don't use Word) like Notepad on Windows, 
TextEdit on Mac OS X or Gedit on Linux-based distributions. You can write or copy and paste, 
but it's an easy way to write text that can quickly be turned into HTML. The web is written in 
HTML, so think of it like quick-start web developing for content editors. When you write in 
Txt2tags, you save the document with the file extension `.t2t`. More often than not, you'll 
never need to save a Txt2tags document, because you'll be using online tools.

## Take action! 

Demand that your projects be built with Txt2tags.

<hr/>

<h1>Markdown support</h1>

## Hey markdown users, we have heard you! 

You can reuse some of your markdown habits within txt2tags. In fact you 
can almost reuse all of the markdown syntax:

 * Unordered lists in txt2tags begins with -, not *. But we can set-up 
a `preprocessor` so it can handle the * in addition.
 * Ordered lists in txt2tags begins with +, not 1. But again, we can
change this. Look at this (look at the source in fact...):

1. Here is a list
1. Another
1. Etc.


 * Markdown links are supported as well. Here is a link to the [txt2tags website](http://www.txt2tags.org). 
Unfortunately, we can't use reference links in this little hack to support most of the markdown syntax. 


>  And quotes are supported too.

Of course, you can't use the single * or _ for emphasis and the double ones for strong like for markdown: 
technically it's possible, but in txt2tags we use double symbles, `**, //, -- and __` for respectively 
**bold**, *italic*, strike and underline. The ***bold italic*** style is also supported as a 
combination. We also use a double ``` for `code`. If some marks are not shown, it's a limitation 
of markdown or github, not **txt2tags** ;)

## It sounds marvellous. How can I do this? 

Just copy this .t2t file and keep the first lines beginning with `%!preproc` `%!postproc` or 
`%!postvoodoo`, it's the regular expression used to integrate markdown into txt2tags.

<hr/>

## Info 

 * This page was made with [Txt2tags](http://txt2tags.org) 

 * Feel free to fork this page and edit, let's [make it better](https://github.com/farvardin/whatistxt2tags/). 

 * This page is based on some reasonings made for markdown, another tool similar to txt2tags (but less powerful and expressive): 
  * https://github.com/kirkstrobeck/whatismarkdown/


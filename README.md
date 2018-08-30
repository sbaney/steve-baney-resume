# About Steve Baney's Resume Project

## Jekyll / GitHub Pages

I've been interested in Jekyll for a while but hadn't quite found the right project to use it for in my professional career, and my resume seemed like a perfect opportunity to get my feet wet. I'm not running any personal websites at the moment and knew that if I spun up a VPS it would be a day or two of playing with server configurations, config management, and documentation, so I decided to try out GitHub Pages. I'll probably migrate this project to it's own server at some point, but the resume is more about the content than the presentation at the moment.

## Content

I use Markdown wherever I can, and already had the rough draft of my resume typed up in Markdown, so dropping that in a folder and having the content mostly set felt great. [Sublime Text 3](https://www.sublimetext.com/) is my editor of choice, and all of the content and code was composed in Sublime.

## Theme

By the same logic I didn't want to build a theme from scratch if I didn't have to, and fortunately the [Minimal](https://github.com/orderedlist/minimal) theme by [Steve Smith](https://github.com/orderedlist) looked to be pretty close to the layout I wanted. I tend to learn best from examples, and the documentation was pretty good, so I was up and running pretty quickly. I made some minor tweaks to the HTML layout to suit my needs, and found customizing the CSS a piece of cake.

## Screen Layout

The only major change I made to the layout is resizing the columns to add more width to the main content area. I also discovered that the content wasn't properly wrapping on mobile, so I did some minor tweaks to the media queries to fix that.

## Print Layout

I really like the screen layout, and messed around a bit with making the print layout match, but I was having issues keeping it under two pages and decided to stick with the default print layout. The only modifications I made were removing some of the unnecessary elements to streamline the print version, as I used this as the source for the PDF version. I thought about using some color but decided that my resume may get printed out and sticking to black and white would be safer.

## Colors

I'm a huge fan of Ethan Schoonover's [Solarized](https://ethanschoonover.com/solarized/) theme, and use it for my text editor, consoles, I even made a Slack theme. So, naturally, I used it for the web version of my resume. I figured a little color and a dark theme would make it stand out a bit. I debated using Solarized Light for the PDF version and may still do so, but for now I figured black and white is safest.

## Fonts

I'm a bit of a font geek, but I have pretty boring favorite fonts. I'm with [Jeff Atwood](https://blog.codinghorror.com/revisiting-programming-fonts/) on Consolas as my programming font of choice, and being primarily on a Windows machine, I tend towards Verdana for Sans and Georgia for Serif fonts on the screen. I am currently second-guessing myself and will probably change this all, but I went with my "defaults" in order to finish in a reasonable amount of time. I'm also debating changing the fonts for the print version, but I'm guessing that will mainly be viewed in PDF on a screen anyway. This all needs work.

## Logo

I wanted to make a quick and simple logo for myself, so I fired up [Paint.NET](https://www.getpaint.net/), my graphics editor of choice (I don't do enough graphics work to justify an Adobe subscription at the moment) and got to work. I wanted something simple and text-based that conveyed my technical / programming background. The colors are pulled from Solarized so it would cleanly drop into the page. I looked around for a monospace font with some serifs to add character and found [TeX Gyre Cursor](http://www.gust.org.pl/projects/e-foundry/tex-gyre/cursor/index_html), which fit the bill perfectly and was licensed for free use to boot.  So I wrapped my initials in some brackets to add some "programmer-y" flavor and good to go.
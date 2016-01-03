# Data Disarray

## Extracting and Making Sense of OSM Data
By Christy Heaton

_Press `F` to go full-screen._<!-- .element: class="fragment" data-fragment-index="1" -->

_Try moving `RIGHT`._<!-- .element: class="fragment" data-fragment-index="2" -->



## Where I work

[`SGSI`](http://www.sgsi.com) - Schlosser Geographic Systems Inc

_VAR of Pitney Bowes products._<!-- .element: class="fragment" data-fragment-index="1" -->

_Spectrum Spatial for Web Mapping._<!-- .element: class="fragment" data-fragment-index="2" -->

_MapInfo Pro for Desktop Mapping._<!-- .element: class="fragment" data-fragment-index="3" -->

_Custom applications._<!-- .element: class="fragment" data-fragment-index="4" -->



## The Project

A world base map.

_Using Spectrum Spatial_<!-- .element: class="fragment" data-fragment-index="1" --> 

_Need data in TAB format_<!-- .element: class="fragment" data-fragment-index="2" -->

_We have Pitney Bowes US base map data_<!-- .element: class="fragment" data-fragment-index="3" -->

_But we needed data for the rest of the world_<!-- .element: class="fragment" data-fragment-index="4" -->



### Enter [`Open Street Map`](http://www.openstreetmap.org/)


_What is Open Street Map?_<!-- .element: class="fragment" data-fragment-index="1" -->


## Free and editable web map.
Crowd sourced!

## You can contribute to it.
Like Wikipedia!

## You can also extract data from it for any purpose
For free!



## The Plan

_Download OpenStreetMap data in some kind of database_<!-- .element: class="fragment" data-fragment-index="1" -->

_Convert to TAB format_<!-- .element: class="fragment" data-fragment-index="2" -->

_Add to Spectrum Repository_<!-- .element: class="fragment" data-fragment-index="3" -->

_Style per customer request_<!-- .element: class="fragment" data-fragment-index="4" -->

_`Web maps!`_<!-- .element: class="fragment" data-fragment-index="5" -->



## You can put images in a slide

![alt text](assets/logo.png "Logo Title Text 1")

![external image](https://raw.githubusercontent.com/maptime/maptime.github.io/master/img/xmaptime-logo-web-header-rainbonly.png.pagespeed.ic.sUvy41gYSf.png "External Image Example")



<!-- .slide: data-background="MintCream" -->
## Style

You can style each slide individually.

_Cool background, right?_<!-- .element: class="fragment" data-fragment-index="1" -->
```
<!-- .slide: data-background="MintCream" -->
## Style

You can style each slide individually.
```



## Hey, it even supports code!

```
var marker = L.marker([49, 5.49]).addTo(map);
var polygon = L.polygon([
  [51.509, -0.08],
  [51.503, -0.06],
  [51.51, -0.047]
]).addTo(map);
marker.bindPopup("<b>Hello world!</b><br>I am a popup.").openPopup();
polygon.bindPopup("I am a polygon.");
```



## Want to see something _really_ crazy?

Press `S` to check out the 'Presentation Mode'.

Note:
The idea is that you put the other window on a shared screen, like a projector, and view this screen on your laptop. Btw, this note is only visible to the presenter.



## That's about it

There are a bunch of cool things you can do with **Reveal.js** and **Markdown**.

Check out Reveal.js' [example slides](http://lab.hakim.se/reveal-js/) for more quick examples of what you can do with Reveal.js.  Check out Reveal.js' [Readme](https://github.com/hakimel/reveal.js/blob/master/README.md) and its [wiki](https://github.com/hakimel/reveal.js/wiki) (especially the [Articles & Tutorials](https://github.com/hakimel/reveal.js/wiki/Articles-&-Tutorials) section) for greater detail about using Reveal.js.  

Check out this [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for a quick intro into using Markdown.

# jquery-svgpan

This is an an adaptation of Andrea Leofreddi's SVGPan library,
version 1.2.2, for use as a jQuery plugin.

When called upon SVG element(s), this will add all the capabilities of
Andrea Leofreddi's SVGPan library to those elements.  Non-SVG elements
will be silently ignored.

[See it in action!](http://talos.github.com/jquery-svgpan/demo.html)

### Usage

You can configure the behaviour of the pan/zoom/drag by passing
arguments.

`enablePan`: Boolean enable or disable panning (default enabled)

`enableZoom`: Boolean enable or disable zooming (default enabled)

`enableDrag`: Boolean enable or disable dragging (default disabled)

`zoomScale`: Float zoom sensitivity, defaults to .2

```javascript
    $(selector).svgPan(enablePan, enableZoom, enableDrag, zoomScale);
```

### Examples

This would enable SVGPan for all SVGs currently on the page.

```javascript
    $('svg').svgPan();
```

This would enable SVGPan for a single element (provided it is an SVG).

```javascript
   $('#id').svgPan();
```

### Links

Andrea Leofreddi's original SVGPan library on Google code

http://code.google.com/p/svgpan/

Fork jquery-svgpan at

http://www.github.com/talos/jquery-svgpan

CDN jquery-svgpan from

http://talos.github.com/jquery-svgpan/jquery-svgpan.js

http://talos.github.com/jquery-svgpan/jquery-svgpan.min.js

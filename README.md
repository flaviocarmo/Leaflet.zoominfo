# Leaflet.zoominfo

## Description
A leaflet zoomcontrol plugin with map zoom level information.

It is a forked/modified code from the nice Leaflet.zoomslider [https://github.com/kartena/Leaflet.zoomslider].

## Requirements

* Leaflet 1.x

## Usage instructions

### Quick Guide

**HTML:**

```html
<!-- add L.Control.Zoominfo js and css after Leaflet -->
<link rel="stylesheet" href="L.Control.Zoominfo.css" />
<script src="L.Control.Zoominfo.js" ></script>
```

**JavaScript:**

```javascript
var map = L.map('map', {
  zoomsliderControl: true,
  zoomControl: false,
  zoom: 12, 
  center: [-15.597821, -56.094979]
});
```

## License

L.Control.Zoominfo is distributed under the [Apache 2.0 License](http://choosealicense.com/licenses/apache-2.0/).

leaflet-pulse-icon
=====================
<div style="text-align:center" align="center">
  <img src="http://mapshakers.github.io/projects/leaflet-pulse-icon/leaflet-pulse-icon.png" alt="leaflet-pulse-icon" />
</div>

A very simple [Leaflet](http://leafletjs.com) plugin provides pulsing icon.

*Requires Leaflet 0.7.0 or newer and modern browser*

## Demo
[Check out demo!](http://mapshakers.github.io/projects/leaflet-pulse-icon)
## Using the plugin
#### Add the JavaScript and CSS files

Include the CSS and JavaScript files located in ```\src``` folder.

```html
<script src="src/L.Icon.Pulse.js" />
<link rel="stylesheet" href="src/L.Icon.Pulse.css" />
```

### Usage
Create a new L.Icon.Pulse

```javascript
var pulsingIcon = L.icon.pulse({iconSize:[20,20],color:'red'});
var marker = L.marker([50,15],{icon: pulsingIcon}).addTo(map);
```
### Options
| Property        | Description            | Default Value | Possible  values         |
| --------------- | ---------------------- | ------------- | ------------------------ |
| color           | color of icon         | 'red'         | any CSS color            |
| iconSize        | size of L.divIcon      | [12,12]       | <Point> [width,height]   |


## License
**leaflet-pulse-icon** is free software, and may be redistributed under the MIT-LICENSE.


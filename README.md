# OpenLayers 3 Map snapshot

ZoomToMaxExtent control for an [OL3](https://github.com/openlayers/ol3) map.

This module has been initially developed for the needs of the OpenFIGIS [FigisMap](https://github.com/openfigis/FigisMap) project used as web-mapping framework in the FAO Fisheries & Aquaculture [website](http://www.fao.org/fishery/en), principally through the Fisheries Global Information System (FIGIS).

## Status

The plugin has been **successfully tested** and, for information, it is used in production in [FIGIS](http://www.fao.org/fishery/topic/18042/en).

For users/developers interested in contributing, contributions, bug reporting and/or fixing are more than welcome! If you have questions or suggestions, please do not hesitate to [contact me](mailto:emmanuel.blondel1@gmail.com)

## Examples

The examples demonstrate usage and can be viewed online thanks to [RawGit](http://rawgit.com/):

* [Basic usage](http://rawgit.com/eblondel/ol3-snapshot/master/examples/snapshot-default.html)
   * Create a map instance with a basic Snapshot control
   
## API

### `new ol.control.Snapshot(opt_options)`

OpenLayers 3 Snapshot.

See [the examples](./examples) for usage.

#### Parameters:

The ``ol.control.Snapshot`` accepts a single ``opt_options`` parameter (of type ``Object``) that extends ``olx.control.ControlOptions``, and accepts the following properties:

|Name|Type|Description|
|:---|:---|:----------|
|`className`|`String`| control CSS class name. Default value is ``ol-snapshot``|
|`label`|`String`| Label displayed as control button. Default value is camera image html markup that will displays as button|
|`tipLabel`|`String`| Tip label displayed on mouse over the control button. Default value is ``Snapshot``|

#### Extends

`ol.control.Control`

#### Methods



###### Parameters:

|Name|Type|Description|
|:---|:---|:----------|
|`map`|`ol.Map`| The map instance. |

## License

MIT (c) 2019 Emmanuel Blondel

## Contributors


## Applications

* [FigisMap](https://github.com/openfigis/FigisMap) Javascript API for the Fisheries Global Information System (FIGIS)

## Sponsors

* UN FAO FI Department, as part of the [Fisheries Global Information System](http://www.fao.org/fishery/topic/18042/en) (FIGIS)
[![FIGIS](http://www.fao.org/figis/servlet/IRS?iid=17437)](http://www.fao.org/fishery/topic/18042/e)

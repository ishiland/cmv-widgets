# WMS Basemaps
Use WMS layers as basemaps for the Configurable Map Viewer (CMV). Works in place of the core CMV basemap widget.

## Features
- Supports multiple WMS Servers.
- Works in both 'agol' and 'custom' modes.
- WMS layer loading icon

## Notes
- the `mapStartBasemap` must be a custom supported or AGOL basemap, not a wms layer.
- the wms layer spatial reference must match the `mapStartBasemap` basemap
[See Here](http://docs.cmv.io/en/1.3.4/configure/basemaps/) for more info on supported starting basemaps.

## Configuration

```js
            // sample configuration
            wmsBasemaps: {
                include: true,
                id: 'wmsBasemaps',
                type: 'domNode',
                path: 'gis/plugins/WMSBasemaps',
                srcNodeRef: 'basemapsDijit',
                options: 'config/wmsBasemaps'
            },
```


## demo
Check it out in action [here](https://ishiland.github.io/cmv-widgets/).
# Advanced Draw
Advanced Draw Widget for the Configurable Map Viewer (CMV).

This widget was slightly modified from the codebase found [here](https://github.com/stevenjh/advanced-draw-widget/tree/development).

## Features
- Add text to map
- Redo and Undo drawn features
- Snap to existing features   
- Specify Outline, Fill and Width properties

## Configuration

```js
            // sample configuration
            advancedDraw: {
                include: true,
                open: false,
                position: 1,
                id: 'advancedDraw',
                title: 'Advanced Draw',
                iconClass: 'fas fa-fw fa-pencil-alt',
                type: 'titlePane',
                path: 'gis/dijit/AdvancedDraw',
                options: {
                    map: true,
                    mapClickMode: true
                }
            }
```
## demo
Check it out in action [here](https://ishiland.github.io/cmv-widgets/).
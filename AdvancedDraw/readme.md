# Advanced Draw
Advanced Draw Widget for the Configurable Map Viewer (CMV).

This widget was slightly modified from the codebase found [here](https://github.com/stevenjh/advanced-draw-widget/tree/development).

## Features
- Add styled text and geometries to map
- Right click drawing to edit
- Redo and Undo drawn features
- Snap to existing features   

## Configuration

```js
            // sample configuration
            advancedDraw: {
                include: true,
                open: true,
                position: 3,
                id: 'advancedDraw',
                title: 'Advanced Draw',
                iconClass: 'fas fa-fw fa-pencil-alt',
                type: 'titlePane',
                path: 'gis/plugins/AdvancedDraw',
                options: 'config/advancedDrawConfig'
            },
```
## demo
Check it out in action [here](https://ishiland.github.io/cmv-widgets/).
# Advanced Draw
Advanced Draw Widget for the Configurable Map Viewer (CMV).

## Features
- Add styled text and symbols to the map
- Right click drawn feature to edit text/symbols
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

## Acknowledgments
This widget has been modified from the codebase found [here](https://github.com/stevenjh/advanced-draw-widget/tree/development).

## demo
Check it out in action [here](https://ishiland.github.io/cmv-widgets/).
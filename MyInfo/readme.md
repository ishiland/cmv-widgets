# My Info
A widget for the Configurable Map Viewer (CMV) to display HTML attached to a specified dom node. Useful for displaying information about your organization such as links, contact information and logos.


## Configuration

```js
            // sample configuration
            myInfo: {
                include: true,
                id: 'myInfo',
                type: 'floating',
                title: 'MyInfo',
                preload: true,
                path: 'gis/plugins/MyInfo',
                options: {
                    attachTo: 'sidebarLeft', // the dom node to place MyInfo
                    position: 'last', // “first”, “last”, or “only”
                    href: 'js/config/myInfo.html' // provide HTML
                    // content: '<div>My Content</div>' // or pass in a string as an alternative to href
                }
            },
```

sample html config is available in this repo.

## demo
Check it out in action [here](https://ishiland.github.io/cmv-widgets/).
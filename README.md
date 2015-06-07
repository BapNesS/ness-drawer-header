ness-drawer-header
============

`ness-drawer-header` is a dedicated header to setup into the <a href="https://github.com/PolymerElements/paper-drawer-panel/blob/master/paper-drawer-panel.html">paper-drawer-panel</a>. User can display profile picture, personal informations and a Google Maps link for the city/country properties.

Example:
```html
<ness-drawer-header first="Jon" last="Snow" age="17" city="Winterfell" country="Westeros"></ness-drawer-header>
```

For now, there's no default values for the properties so the behavior could be a quite ugly without them.

## Styling

The following custom properties and mixins are available for styling:

Custom property | Description
----------------|--------------
`--ness-drawer-header-picture-theme` | Profile picture
`--ness-drawer-header-link-hover`    | Google Maps link when hover
##&lt;app-drawer&gt;

app-drawer is a navigation drawer that can slide in from the left, right, bottom or top.

Example:

Add a drawer on the left side of the screen:

```html
<app-drawer opened></app-drawer>
```

Add a drawer on the right side of the screen:

```html
<app-drawer position="right" opened></app-drawer>
```

### Styling

Custom property                  | Description                            | Default
---------------------------------|----------------------------------------|--------------------
`--app-drawer-content-container` | Mixin for the drawer content container | {}
`--app-drawer-scrim-background`  | Background for the scrim               | rgba(0, 0, 0, 0.5)
ui-grid
=======

A WebJar for the angular ui ui-grid project.  http://angular-ui.github.io/ng-grid

ui-grid is the successor of ng-grid v2.0. I don't know if they will change their repo.
http://angular-ui.github.io/ng-grid/

The build works but is suboptimal, because somehow all old versions seem also to be contained in the zip as of version 3.0.0-rc.11.

For play2.0 my require.js config looks like:

```
'ui-grid': ['../lib/ui-grid/release/3.0.0-rc.11/ui-grid']
```

and I have to add:

```
<link rel="stylesheet" href="@routes.Assets.versioned("lib/ui-grid/release/3.0.0-rc.11/ui-grid.min.css")" />
```
on the html template of the page.

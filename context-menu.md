# Context Menu (Right-click menu) on the canvas
## How does it work
- A JavaScript function detects right click ([oncontextmenu](https://developer.mozilla.org/en-US/docs/Web/API/Element/contextmenu_event)) event.
- This event sets the location of the context menu to the coordinates of the right click.
- When any option is clicked on the context menu, respective JS functions are triggered.
- These functions set respective variables to true & a setInterval function detects the value. If the value is true, the CSS rules of the canvas are changed i.e *cursor:crosshair*. If not, it sets the CSS rules to *cursor:default*.

<div align="center"><i>--END OF MARKDOWN FILE--</i></div>

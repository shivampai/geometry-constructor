# Toolbox
## Reference URLS : 
### Line Segment Based :
- [Line Segment Equation Finder](line-segment-equation.md)
- [Divide Line Segment In A Particular Ratio](divide-line-segment-in-ratio.md)
- [Trisect a line segment](trisect.md)
### Triangles Based : 
- [Classify Triangle](classify-triangles.md)
- [Area of a triangle](area-of-a-triangle.md)
### Circles Based : 
- [Check if a point lies on a circle](if-point-on-circle.md)
- [Check if a point lies inside the circle](if-point-in-circle.md)
## How tools appear when selected : 
- When the user changes the value of the select tool dropdown, a JS function is triggered.
- The JS code is implemented in 2 stages :
    1. Hiding all the `.tool-section` divs (holds the HTML code of each of the tools).
    2. Showing the target tool.
- The dropdown has values as per the DOM element number of the respective `.tool-section` div.
- Using a [for loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for) of array ```document.querySelectorAll('.tool-section')```, each of the div is set to `style:display:none`.
- The index DOM element number of the input is shown using DOM.style.display = 'block' method.

<div align="center"><i>--END OF MARKDOWN FILE--</i></div>

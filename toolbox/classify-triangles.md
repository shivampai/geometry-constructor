# Classify Triangle (by length)
## How it works : 
- User inputs the Vertices of the triangle in the 3 dropdowns (`.points-as-options`).
- Button Onclick event triggers a JS function.
- The JS function finds the length (```findLengthOf(lineName)```) of all 3 sides of the triangle.
- The lengths are then compared :
   - If A,B,C are the vertices of triangles,
   - AB == BC == CA; the triangle is **equilateral**.
   - (AB == BC != CA) || (BC == CA != AB) || (AB == CA != BC); the triangle is **isoceles**.
   - AB != BC != CA; the triangle is **scalene**.
- The output is shown on a *Label* element present under the button

<div align="center"><i>--END OF MARKDOWN FILE--</i></div>

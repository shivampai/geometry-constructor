# Triangle Area Calculator
## How it works : 
- The user inputs the vertices of the triangles using 3 dropdowns (`.points-as-options`).
- On button click, a JS function is triggered.
- The length of all sides of the triangles are calculated using `findLengthOf(lineName)` function.
- The sides of the triangle are stored in 3 variables : *a , b & c*
- Using **HERON'S FORMULA** i.e $$area = \sqrt(s(s-a)(s-b)(s-c))$$ where s = **Semiperimeter of the triangle** i.e $$s = (a + b + c)/2$$.
- The output is then displayed on a `span#tools-area-of-triangle-output`.

<div align="center"><i>--END OF MARKDOWN FILE--</i></div>

# vizabi-interpolators
Interpolation algorithms shared between vizabi and waffle-server

### API: 
All interpolators accept the same inputs: x1, x2, y1, y2 - boundary points, x - point of interpolation  
`interpolator.<linear|exp|stepBefore|stepAfter|stepMiddle>(x1, x2, y1, y2, x)`

and return the interpolated value y.


### Supported algorithms:  

![image](https://cloud.githubusercontent.com/assets/3648190/12812560/f7e50470-cb32-11e5-9c79-7b57e528aa6d.png)

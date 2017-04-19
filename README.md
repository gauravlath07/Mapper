# Mapper

### About
Mapper is an Android based application which gives you the shortest distance to walk from point A to point B. 
Possible applications - 
* Amusement parks
* Building floor plans and more...

All you need to do is upload a map in svg format and Mapper will make it interactable.


### How it works ?
The application uses a self impelemented "wall following algorithm" through which it avoids obstacles and finds the shortest path.
Mapper uses a pedometer algorithm, by identifying patterns from the accelerometer readings in a finite state machine to determine when a step is taken. The senser data is cleaned of noise and bias by using a low pass filter which attenuates high frequency signals




| Singal Attenuation  | Map |
| ------------- | ------------- |
| <img src="/img/d1.png" width="300">  | <img src="/img/d7.png" width="300">  |

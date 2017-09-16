# Ray-Tracer
A Ray tracer to parse 3D Scenes.
This is a group project cooperated with my classmates: _Siqisun_ and _Ziyinqu_ for course _CIS 560: Computer Graphics_.
## Sample images:
#### Cornell box reflection and refraction
![Cornell_refelec](https://github.com/Aieener/Ray-Tracer/blob/master/cornell_reflec_refrac.png?raw=true "Optional Title")
#### Cornell box reflection only
![Cornell_refeleconly](https://github.com/Aieener/Ray-Tracer/blob/master/cornell_reflectonly_result.png?raw=true "Optional Title")
#### Primitive shapes
![Primitive_shapes](https://github.com/Aieener/Ray-Tracer/blob/master/my_shapes.png?raw=true "Optional Title")
#### Render 3D image with mesh data structures
![Primitive_shapes](https://github.com/Aieener/Ray-Tracer/blob/master/gourd.png?raw=true "Optional Title")

## To run the program
This is a **Qt project (tested on Ubuntu 16.04)**, so to run the program, just modify the main.cpp as there are multiple
scenes/version of raytracers to test on, i.e:
```c++
	QImage image = raytracer("../json/cornell_box.json"); //reflection + refraction    
	//QImage image = accraytracer("../json/cornell_box.json"); // reflection only
	...
```
Then press the `run` button in Qt.

P.S. if there is an error about 
```
"'it' does not name a type for(auto it = triangle...)"
```
just add `CONFIG += c++11 `into the .pro file.

Thanks ;)!

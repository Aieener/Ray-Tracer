# Ray-Tracer
A Ray tracer to parse 3D Scenes.
This is a group project cooperated with my classmates: Siqisun and Ziyinqu for course CIS 560: Computer Graphics.

To run the program: (tested on Ubuntu 16.04)
This is a Qt project so to run the program, just modify the main.cpp as there are multiple
scenes/version of raytracers to test on, i.e:
		QImage image = raytracer("../json/cornell_box.json"); //reflection + refraction    
		//QImage image = accraytracer("../json/cornell_box.json"); // reflection only
		...
Then press the run button.

P.S. if there is an error about "'it' does not name a type for(auto it = triangle...)", just add
CONFIG += c++11 into the .pro file.

Thanks!

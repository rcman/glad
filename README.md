Someone was having issues compiling this so I looked in to it.

I went to this link which told me to open the link below to get glad.

https://glad.dav1d.de/

Picked gl version 4.5 and left the same. Selected Local files, then generate.

It gives you files but that's not what used.

I'm on linux so I needed to download glfw3 with this command.     sudo apt install libglfw3-dev -y

that installed. The copied the code below and run it with my framework. src, include and release directory

My Sconstruct looked like this for libaries

SDL2_mixer SDL2_image SDL2_ttf SDL2 glut GLU GL glfw dl

Then rab scons on the code and it works fine.




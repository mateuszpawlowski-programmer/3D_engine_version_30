My 3D software renderer game engine that loads doom e1m1 map.<br>
After software renderer project I try to load 3d .obj files of maps from games like doom,quake and tomb raider :D<br>
And It works pretty well :D so i decided to make simple game on e1m1 map from doom.<br>
This project is quite big :D its something about 18500 lines of code :D.<br>
Renderer works using vertices and faces that are load from files .obj. And then program makes triangles objects from them. After that all triangles are calculated in 3d space and projected at 2d screen space :).<br>
There is straight clipper method inside projection equation instead of clipping triangles. There is also few sort orders of triangles depending on distance from player. At the end triangles are drawn from farthest to nearest.<br>
There are special doors,characters and car objects, collision model and stairs system. Of course you can shoot in game using guns :D and there is bullet projection and detection in 3d space. There is also combat Ai behavior alorithm of enemies.<br>
I am really happy that I make this project. I hope you will enjoy it. :)<br>
After this game I decide to make another game with intro on this engine using camera and cars animation. That game is Samurai Commando.<br>
<br>
Here are some screens :) I hope you will enjoy it.<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_1.png)<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_2.png)<br>
After shoot enemy doors opens. There are special object in game that represents doors.<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_3.png)<br>
Interesting flag in code in R_3D.java is calculate_lambo when is set on true engine loads laborghini model inside map. :D<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_4.png)<br>
Game have special stairs system that player can walk up and down.<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_5.png)<br>
Another interesting flag in R_3D.java is show_collision when is set on true you can see collision model working on bounding boxes.<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_6.png)<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_7.png)<br>
Another interesting flag in R_3D.java is wire_frame when is set on true you can see wire frame model of level geometry.<br>
![alt text](https://github.com/mateuszpawlowski-programmer/3D_engine_version_30/blob/main/3d_v_30_8.png)<br>

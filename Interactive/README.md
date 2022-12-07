# Interaction
<img src="https://user-images.githubusercontent.com/71798241/206271853-6774576f-5edf-4715-b123-ff023ffa636b.JPG" width="800" height="500" />
<br><br>
# Model Loading
- In total 7 object are loaded into the application from blender (.obj files), all initialised as meshes variables.
<img src="https://user-images.githubusercontent.com/71798241/206271208-9cc453e8-9870-4ea3-a7fe-2d3a89380067.JPG" width="800" height="500" />
<br>
- These meshes variables are loaded as .OBJ files and are located within the Pipleline Interaction folder of the project.
- The obj mesh variables are all assigned in the loadModels helper function and assigned inside the startup method
<img src="https://user-images.githubusercontent.com/71798241/206272025-20567ad7-5d4c-46dd-bb13-fc8a10d1d9dc.JPG" width="800" height="500" />
<br>
- Each of the objects are positioned in certain 3 point vectors location when window is starting.
<img src="https://user-images.githubusercontent.com/71798241/206272346-60f3ad12-e747-43c9-ade1-700eb342630c.JPG" width="800" height="500" />

<br><br>
#Shaders
- Fragment shaders handle lighting, colours, shadows and many other important aspects. In the fragment shader I utilise, several constants and uniforms are declared.

- Ambient, Diffuse, Specular and Shininess uniforms are declared, along with their corresponding colours. These can be accessed from the source code and assigned values.
<img src="https://user-images.githubusercontent.com/71798241/206273106-787334b5-a282-41e4-aeff-4a5f37eeb622.JPG" width="800" height="500" />
<br><br>

- Vertex shaders handle the programmable shading of individual vertices. Uniforms are declared handling the several matrices used in the code. The matrices are used for positioning objects.
<img src="https://user-images.githubusercontent.com/71798241/206273505-23007c2b-b210-419a-b05a-44d65e31e5eb.JPG" width="800" height="500" />

<br>
#Lighting
- Ambient, Diffuse and Specular lighting is first declared here.
<img src="https://user-images.githubusercontent.com/71798241/206273569-3c474ac1-d101-4508-989e-7d7ca5d2d116.pn" width="800" height="500" />

<br><br>
#Interactivity
- The model's rotation can be controlled using the UP, DOWN, LEFT and RIGHT arrow keys.
- The exploration camera can be controlled by pressing the W, A, S, D keys to go forwards, left, backwards and right respectively. It can also be moved up and down on the y-axis using the space and tab keys.
<img src="https://user-images.githubusercontent.com/71798241/206274017-c4992058-4620-4651-acb0-5d34646ffa38.JPG" width="800" height="500" />


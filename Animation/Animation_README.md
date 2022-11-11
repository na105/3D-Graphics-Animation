Animation
The animation process was done using Unreal Engine 5. Through the process, I managed to export the blender scene to an .fbx file and importing it in unreal engine. Afterwards, I handled the untextured objects that were sadly not exported such as the floor, couch, and one side of a wall by using real engine textures. Finally, after managing the scene I proceeded to include some animations such as flickering lights and door opening using blueprints and nodes and using cameras to include these scenes in level sequences.
<br><br>
<p align="center">
<img src="https://user-images.githubusercontent.com/71798241/201417748-976bf0de-e79c-4e0a-a453-4463502693a4.JPG" width="800" height="500" />
</p>

<br><br>

Animation Process:

1. Lights Flickering:
I used the usage of EmissiveColor to give the illusion of lights flickering to give the dimly lit scene more 
<p align="center">
<img src="https://user-images.githubusercontent.com/71798241/201419158-c52801bb-b6fc-45e5-b348-86056d16d501.JPG" width="800" height="500" />
</p>

2. Door opening:
The usage of the box collision was to intrepert the camera and also triggered in the sequence. With the trigger the blueprint intitiated the process of the door rotating 90 degrees.
<p align="center">
<img src="https://user-images.githubusercontent.com/71798241/201420789-1f48eba6-9733-41cf-b04b-d85ffe8a5f2c.JPG" width="800" height="500" />
</p>


Camera Setup:
The scene was filled Cine Camera Actors used in various sequences to perceive multiple shots of the crime scene. Later, in a final level sequence I joined all the shots to be rendered in one video.

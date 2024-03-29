# Creating a Scene

By: Natalie Hoffmann, March 17, 2024

In my experience as a CAGD minor, I've had to use Unity in every class I've taken. [Unity](https://unity.com) is a video game engine that allows a person to create video games with much more ease rather than doing it from complete scratch. One of the things about unity is being able to create game objects in the scene, and making changes to that object to fit your needs.

The way to do this is by right-clicking in the hierarchy and selecting the object you want to create. The game object will then be added to the scene and be listed in the hierarchy.

<img src="../assets/Creating_GameObject.png" height=300 /> <img src="../assets/GameObject_InScene.png" height=300 />

Once the object is in the scene, you can rename it, change the position, rotation, and scale, add assets, and change the material. Unity provides multiple different ways to accomplish these tasks, for the most part, which provides veteran users with shortcuts that make creating a scene much faster. 

When adjusting the transform of the object, which is the position, rotation, and scale, you can either type in the inspector window, which shows all the properties of the selected object, or use the tools. The object's transform is based on the X, Y, and Z axes, with Y representing the verticle positioning of the scene, much like how a 2D graph uses the Y-axis as the vertical axis. This provides the software with the quality of **"match[ing] between the system and the real world"**, one of the [10 usability heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/) created by Jakob Nielsen.

<img src="../assets/XYZ_Based.png" height=100 />

When adjusting the transforms of an object, using the tools is much less precise than typing in the values in the inspector, but using the tools helps with making large changes or visualizing before making exact adjustments with the inspector. Like with other applications, you can use Cmd+Z (for Apple) or Ctrl+Z (for Windows) to undo any action, which means that Unity not only provides **"recovery from errors"** but also **"consistency and standards"**, two more of the 10 usability heuristics.

<img src="../assets/Move_With_Tool.gif" max-height=200 max-width=320 /> <img src="../assets/Move_With_Numbers.gif" max-height=200 max-width=320 />

Not only are there multiple ways to adjust the transform of an object, but there's a list of ways to add properties to an object.

Drag the property from the project window, which holds all the assets and packages of the Unity project, to the objects name in the hierarchy: 

<img src="../assets/Script_Drag_Drop_Hierarchy.png" max-height=200 max-width=320 /> 

Drag it from the project window to the object in the scene: 

<img src="../assets/Script_Drag_Drop_Object.gif" max-height=200 max-width=320 />

Select the object and drag it from the project window to the inspector window: 

<img src="../assets/Script_Drag_Drop_Inspector.gif" max-height=200 max-width=320 />

Search for it in the inspector: 

<img src="../assets/Script_Search.png" max-height=200 max-width=320 /> 

All these options lead to Unity's success in **"flexibility and efficiency of use"**, yet another one of the 10 usability heuristics, because of all the ways a user can accomplish one task.

Something where Unity's usability falls apart is the way that adding materials, or colors, to an object works. While you can drag and drop the material from the project window to the object in the hierarchy or scene, you can't drag it or search for it in the inspector. While this is something I'm used to as a veteran user, it likely wouldn't match a new user's **mental model** because Unity itself trains users to think that it would be possible.

<img src="../assets/Search_Material.png" max-height=200 max-width=320 /> 

When right-clicking on an object's material in the inspector, there's an option to "select material" which led me to believe that it meant that I would be able to select a *new* material; however, it just selected the material that was being used in the project window. This felt misleading, and I'm also not clear what the purpose of this function is. While it could be used to adjust the material values, all of the material's information is already present and adjustable in the inspector when the object is selected.

<img src="../assets/Select_Material.png" max-height=200 max-width=320 /> 

For the most part, Unity has a decently user-friendly design. I think a good way to fix the issue surrounding the material is by allowing the user to search for it and drag it in the inspector like all the other properties. Changing "Select material" to "select material in assets" would also be beneficial since the original wording is too ambiguous.

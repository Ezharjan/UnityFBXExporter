# FBX Exporter

This tool is more powerful when being utilized with other 3D designing tools.


### Case 1: 
Merging multiple parts of an FBX into a single one so as to use the FBX in the project cleanly:
1. Import your FBX file into this tool;
2. Pack them with an empty object as the root node;
3. Set the origin of the first children node into center; 
4. Revise as you wish, Eg: you can make transforms or even assign an animation for your gameobject in Hierarchy;
5. Right click the target `gameobject` and choose `Export to FBX`;
6. Choose `Binary` to reduce the size of your exported FBX file, view `ExportSettingsRef.png` as a reference.
7. Import the exported FBX file into `Blender` or any other 3D designing tools;
8. Select the parent node of the model and export it as an `OBJ` file with its textures tightly bound with itself;
9. Goto `1.` and do it again till you reach `6.`, the FBX file exported will be cleaner as it only contains a single child under a root;
10. Generating colliders is a **must**, refer to [MeshColliderGenerator.URL](https://stackoverflow.com/questions/62469062/wrong-mesh-collider-when-import-fbx-from-blender-to-unity) while generating the colliders.



<br>
<br>
<br>

by Alexander Ezharjan
# maya-scene-splitter
Let’s say you have a bunch of objects in Maya on your scene that you need to export to an art repository, for example.
Using this script, it will save all objects in the scene into separate .mb files.
The file names are automatically taken from the names of the objects in the scene.

Details: If there’s a group of objects, it saves the group as a separate file, but it also saves the individual objects within the group as separate files. Essentially, you can just delete those extra files if you don’t need them.

The script is written in MEL. It creates a folder on the desktop and saves everything there. If you want, you can change the path in the code.

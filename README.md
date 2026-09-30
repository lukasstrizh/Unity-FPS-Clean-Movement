\# Clean FPS Movement



\### === How to Set Up FPS Player Movement ===



1\. \*\*Add the Player prefab\*\* to your scene.



2\. \*\*Assign the "Player" layer\*\* to the Player prefab and all of its children (or use any custom layer except "Default").



3\. \*\*Set the "Ground Mask"\*\* in the Player Movement component to \*\*"Default"\*\* (or the specific layer your map is on). If the layer of your map is not included in the Ground Mask, the script won't detect the ground, which will break the movement velocity and jumping.




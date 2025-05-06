## Blender Mesh Toolkit Addon

_A simple addon for creating, managing, and merging mesh cubes in Blender._

![image](https://github.com/user-attachments/assets/412127f5-59cd-408b-afc8-1f5477afd44d)
---

This addon was developed as the solution of the screening test for FOSSEE (https://fossee.in/) under Task 1 of the OpenFOAM GUI project selection process. The screening tests were the evaluation step for the FOSSEE Summer Fellowship 2025, a summer internship program at IIT Bombay.



🔥 Features of the addon:

**Feature Set 1: Cube Grid Generator**
1. **UI Panel**: A panel named **FOSSEE_ADDON** is added to the 3D Viewport sidebar.
2. Enter a number N ε [0,20] to generate a 2D grid of cubes (of side length = 1 Blender unit).
3. Cubes are evenly distributed in an m x n grid (no overlaps).
4. The new cubes does not overlap with any existing ones.  
5. A spearate collection for every instance of creation of cubes.
6. A button for deletion of selected meshes.


Feature set 2:
1. In the same UI as Feature set 1, there is a button which merges the selected cubes (which were generated using this Add-on) into a single mesh.
2. To be able to merge 2 meshes, they should have at least 1 common face.
3. When merging, the common vertices are merged into a single vertex, and the common face is deleted.

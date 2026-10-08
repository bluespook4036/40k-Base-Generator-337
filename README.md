# 40k-Base-Generator-337
A blender tool for generating bases of nearly every legal size in Warhammer 40000 11th edition, and a tool for generating rocks for your bases as well.

User Guide:

You can access the tool by downloading Base-Generator.blend and opening the file in Blender.
*NOTE - This project was created in Blender 5.2.1 LTS, and may not be compatible with older versions of Blender.

The Base Generator:  - "Basemaker" in the modifiers tab.
After opening the file, your 3D viewport will have an already finished base waiting for you.
To modify this base, navigate to the "Modifiers" section of the base's "Properties" tab.
The parameters editable in-menu are as follows:
1. Base Size - This dropdown menu allows you to select the real-world size of the base that will be generated for you. All standard Warhammer 40k base sizes are included, except for 75x25mm and 95x40mm bases.
2. Terrain Seed - This option can be filled with any number. It influences the noise pattern of the terrain/ground on the base.
3. Rock Seed - This option functions similarly to the Terrain Seed, but directly influences the placement, size, and rotation of the rocks instead.
4. Rock Density - This float ranges from 0-1, and determines the overall number of rocks created, with no rocks at 0, and a very large number of rocks at 1. I recommend keeping this value less than 3.0 to make placing your models easier.
5. Rock options - This dropdown contains the two current rock options, which are collections of rock assets that will be distributed across your base if you choose to include them. The two options are small rocks, and mid-size rocks. Small rocks will likely be about the size of a space marine's boot, but mid-size rocks can be large enough for a full model to stand on top.
6. Low/High Poly - A dropdown menu allowing you to select between two levels of detail in the model. Because this model is meant for print, it is recommended that users primarily utilize the "Highpoly" mode for better detail on export.
7. Bake - Found under the "Manage" tab, the Bake options give you control over where the baked UVs for the model will go when you export it from blender.

The Rock Generator - "RockGenerator" in the modifiers tab.
1. Seed - Randomizes elements of the model, any number can go here.
2. Surface roughness - Used to modify the roughness of the noise pattern ran over the surface of the rock.
3. Sphericality - Used to influence rock shape to be more or less spherical
4. High/Low Poly - functions exactly the same as the high/low poly options for the bases. See above.
5. Modify Size and Size Gizmo - In the modifier tab, you can directly edit the "base mesh" of the rock by changing the dimensions/transforms of a cube that serves as the base for this project. In the viewport, clicking on the model reveals arrow in the x, y, and z directions. Clicking and dragging the arrowhead allows you to modify the model's starting shape.
6. Surface Detail - Used to allow more or less specific details show in the rock.
7. Scale - Allows you to dynamically resize any rock you create.
8. Rotation - allows you to rotate and view a rock from different angles.

   HOW TO MAKE A NEW BASE
   Select the original base and Duplicate (Shift + D) or create a new object and assign the basemaker geonodes in the object's modifier tab.

   HOW TO MAKE A NEW ROCK
   Add any object, and add the rock generator geonodes to the object in the modifier tab. Alternatively, select an existing rock and Duplicate (Shift + D) to tweak the parameters on a new object.

   Thank you for reading, enjoy the tool!

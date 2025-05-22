Changing Third Person Character Mesh and Adding Animations in Unreal Engine
Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

Procedure
Import New Character Mesh and Animations:

In the *Content Browser, import a new *Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).
Replace Character Mesh:

Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the *Details Panel, change the *Skeletal Mesh to the newly imported mesh.
Set Animation Blueprint:

If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.
Preview and Test:

Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.
Output

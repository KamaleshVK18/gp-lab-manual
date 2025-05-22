# Changing Third Person Character Mesh and Adding Animations in Unreal Engine
## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure
```
1.Import New Character Mesh and Animations:

2.In the *Content Browser, import a new *Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).
Replace Character Mesh:

3.Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the *Details Panel, change the *Skeletal Mesh to the newly imported mesh.
Set Animation Blueprint:

4.If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
5.If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
6.In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.
7.Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.
```
Output

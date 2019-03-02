# Libgdx-3D-Character-Example

# Bones moved by Vertex groups:
1. Create a Armature Modifier for the mesh you want to animate, and in "Object" set your armature
2. (Easier way) Select your object, go to "Weight Paint", press CTRL+select the bone you want to assign your vertex groups, paint the mesh.

2. Or... (Manual way) Select your object, create a Vertex Group, and name it with the same name as your bone.
[How do I transfer only single vertex groups between objects?](https://blender.stackexchange.com/questions/45898/how-do-i-transfer-only-single-vertex-groups-between-objects)
# To weight paint multiple objects at the same time, use the "MultiEdit" Blender Addon
https://github.com/Yzubi/MultiEdit-Addon

# Move along vertex / edges (Vertex slide)
g -> g
# Scale individual in Blender
Select faces-> Change to Edge select -> Alt+S
# Bevel vertices in Blender- Similar to Wings 3D
(Ctrl+Shift+B
# Scale Uniform in Blender - Similar to Wings 3D
Select faces-> CTRL + . -> S (Pivot Point = Individual Origins)

Revert with CTRL + , (Pivot Point = Median Point)

# Useful links

- [3D models and animation from Blender to LibGDX](https://www.gamefromscratch.com/post/2014/01/19/3D-models-and-animation-from-Blender-to-LibGDX.aspx)
- [How to see the bones through the mesh?](https://blender.stackexchange.com/questions/110254/how-to-see-the-bones-through-the-mesh) (Object Data -> Display -> Enable X-Ray)
- [Blender - Inverse Kinematics Limits](https://docs.blender.org/manual/en/2.79/rigging/armatures/posing/bone_constraints/inverse_kinematics/introduction.html)
- [Change bone colors](https://www.youtube.com/watch?v=VqTdzPnvpUk) (Pose mode -> Object Data -> Enable "Colors" in "Display" -> Add new bone group in "Bone Groups" -> Select color and assign the color to selected bones.
- [Change bone tickness](https://blender.stackexchange.com/questions/6215/change-size-of-armature-bones)(CTRL+ALT+S in edit mode)
- [NLA Editor Blender](https://docs.blender.org/manual/en/2.79/editors/nla/index.html)
- [Scripting – Change settings the fast way - Blender](https://code.blender.org/2011/05/scripting-%E2%80%93-change-settings-the-fast-way/)
- [Nurbs Tutorial](https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro/NURBS_Patches) (Alt-C to fill Nurbs curve in edit mode)
- [How do I set a background image while I am editing?](https://blender.stackexchange.com/questions/118/how-do-i-set-a-background-image-while-i-am-editing) - [Blender - Noob to Pro - Background images](https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro/Background_Images)
- [Deleting & Dissolving](https://docs.blender.org/manual/en/2.79/modeling/meshes/editing/basics/deleting.html) (Limited Dissolve)
- [Select multiple faces at once](https://blender.stackexchange.com/questions/5004/select-multiple-faces-at-once)
- [Parenting Objects](https://docs.blender.org/manual/en/2.79/editors/3dview/object/properties/relations/parents.html)
- [Automerge close vertex](https://blender.stackexchange.com/questions/39078/using-automerge-editing-things-arent-merging-what-isnt-right)
- [Blender Tip - Adding color to faces](https://www.youtube.com/watch?v=SlQDSvUSsuI) - [Multiple Materials Per Object](https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro/Multiple_Materials_Per_Object) - [Vertex Color](https://blendersushi.blogspot.com/2012/03/basic-working-with-vertex-color.html) - [Face paint using vertex color](https://blender.stackexchange.com/questions/31160/is-it-possible-to-paint-only-on-selected-vertices-in-vertex-paint)
- [Rig and Animate 2D Sprites in Blender for the Web](http://blog.gskinner.com/archives/2018/02/rigging-animated-2d-sprites-part-1.html) - [Blender 2D Face](https://www.youtube.com/watch?v=qwlemxwK-ZE) - [Tutorial Series: Easy Rigging in Blender 3D](https://www.youtube.com/playlist?list=PLvH-_5Bn5fqEhpShYvLQX3563zhZN6V0p)
- [Join bones Armature](https://blender.stackexchange.com/questions/21239/join-bones-in-a-armature) (CTRL+J for Object Mode)
- [How to make an object invisible at a frame](https://stackoverflow.com/questions/8844389/how-to-make-an-object-invisible-at-a-particular-keyframe-without-moving-it-in-bl) (Moving an object outside camera view (g -> z -> -1000) is a good approach, parent the part you want to hide to a bone, and move the bone away.)
- [Is it possible to begin/end parent relationship with animation or keyframe?](https://blender.stackexchange.com/questions/71669/is-it-possible-to-begin-end-parent-relationship-with-animation-or-keyframe) (Or use Copy transforms contraint, select a Object, a bone, and set "Space" to "Pose Space")

- [Is there a way to convert a constraint to a keyframe?](https://blender.stackexchange.com/questions/2533/is-there-a-way-to-convert-a-constraint-to-a-keyframe)
- [Instant, non smooth frame - Set Keyframe Interpolation to constant](https://blender.stackexchange.com/questions/2379/how-can-a-single-curve-interpolation-mode-set-to-constant)
- [Simple 2.5D character creation and animation](https://www.youtube.com/watch?v=54xbZUykMPo) - [Rigging 2D PERSIAN](https://www.youtube.com/watch?v=q8fT1fK_80I) - [Doodle Notes II - Channel](https://www.youtube.com/user/doodlenotes1234/videos)
- [Blender Low poly - Cute Villager Girl](https://www.youtube.com/watch?v=AK56ehoMVRo)
- [Coa Tools - Blender Addon for 2D animation](https://github.com/ndee85/coa_tools)
- [How To Make A Character For Cut Out Animation In Blender 2.79](https://www.youtube.com/watch?v=4lsP-6Dzr6Y)
- [Fbx-conv-installer-Linux](https://github.com/Yzubi/Fbx-conv-installer-Linux)
- [Blender G3D Exporter](https://github.com/Dancovich/libgdx_blender_g3d_exporter)
- [Set object default size, location, rotation](https://blenderartists.org/t/set-an-objects-default-size/677237) (CTRL-A)
- [How to snap part of a mesh to the grid?](https://blender.stackexchange.com/questions/7368/how-to-snap-part-of-a-mesh-to-the-grid)

Random notes: For better compatibility with the Blender G3D Exporter addon. Convert your Curves to Meshes with Alt-C, parent bones with Armature Deform when animating. A good value for 2D animation is "Armature Deform - With Automatic Weights"

# Invert model sides in object mode with: CTRL + M + Y (Mirror, better method)
Or S -> Y -> -1 (Scale, Worse method)

#CTRL+I to invert selection

Vertex connect: Hotkey j
Knife: Hotkey k

#
Snap Menu - Selection to Cursor

Reference
Mode:	Object, Edit, and Pose Mode
Menu:	Object/Object type ‣ Snap
Hotkey:	Shift-S

#
Center camera view to object
1. Select object
2. Shift-S -> Cursor to selected
3. Alt-Home (Center view to cursor)
#

Freely joined bones: Select two bones in edit mode -> CTRL-P -> Keep Offset

To use custom shapes: Bone -> [Display] Custom Shape + Wireframe
Object Data -> [Display] Shapes

# Enabling backface culling:
- Properties panel (N) -> [Shading] Enable textured solid and Backface culling
# Flip face
W -> Flip Normals in edit mode to flip faces
# Alt-Z Textured mode
[Solid material view Mode - Viewport Shading](https://blender.stackexchange.com/questions/26636/how-to-toggle-material-view-mode-by-hotkey-similar-to-alt-z-shift-z)

# Bladecoder Engine Camera FOV and zoom without camera
Set the "Camera FOV" value the same as your Blender "Field of View" camera value

If you want something similar to an "ortographic camera" dont use cameras, and change the Bladecoder "Camera FOV" for zoom in/zoom out

# Blade-Engine-3D-Character-Example
Example of 3D character for Bladecoder Engine / LibGDX, done in Blender 2.79b

# Useful links
- [3D models and animation from Blender to LibGDX](https://www.gamefromscratch.com/post/2014/01/19/3D-models-and-animation-from-Blender-to-LibGDX.aspx)
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
- [Is it possible to begin/end parent relationship with animation or keyframe?](https://blender.stackexchange.com/questions/71669/is-it-possible-to-begin-end-parent-relationship-with-animation-or-keyframe)
- [Is there a way to convert a constraint to a keyframe?](https://blender.stackexchange.com/questions/2533/is-there-a-way-to-convert-a-constraint-to-a-keyframe)
- [Instant, non smooth frame - Set Keyframe Interpolation to constant](https://blender.stackexchange.com/questions/2379/how-can-a-single-curve-interpolation-mode-set-to-constant)
- [Simple 2.5D character creation and animation](https://www.youtube.com/watch?v=54xbZUykMPo) - [Rigging 2D PERSIAN](https://www.youtube.com/watch?v=q8fT1fK_80I) - [Doodle Notes II - Channel](https://www.youtube.com/user/doodlenotes1234/videos)
- [Blender Low poly - Cute Villager Girl](https://www.youtube.com/watch?v=AK56ehoMVRo)
- [Coa Tools - Blender Addon for 2D animation](https://github.com/ndee85/coa_tools)
- [Fbx-conv-installer-Linux](https://github.com/Yzubi/Fbx-conv-installer-Linux)
- [Blender G3D Exporter](https://github.com/Dancovich/libgdx_blender_g3d_exporter)

Random notes: For better compatibility with the Blender G3D Exporter addon. Convert your Curves to Meshes with Alt-C, parent bones with Armature Deform when animating. A good value for 2D animation is "Armature Deform - With Automatic Weights"

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

#
Enabling backface culling
Properties panel (N) -> [Shading] Enable textured solid and Backface culling

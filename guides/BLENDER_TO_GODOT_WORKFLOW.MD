# How to Import from Blender to Godot

This guide explains how to take your 3D creations (like a lunar crater) and bring them into the **LunCoSim** live world.

## The Concept
We want to create a static part of the word (like terrain or a base structure) in Blender and make it interactive in Godot.

**Example**: We have the **Langrenus Crater** in our simulation (`content/maps/Langrenus`). We will follow a similar workflow.

## Prerequisites
1.  **Blender Installed**: Make sure you have Blender (3.0+) installed.
2.  **Godot Configured**: In Godot, go to `Editor > Editor Settings > FileSystem > Import` and ensure the "Blender 3 Path" is set to your Blender executable.

## Step 1: Model in Blender
1.  Open Blender.
2.  Create your crater or base module.
    *   *Tip: Keep it centered at (0,0,0).*
    *   *Tip: 1 Unit in Blender = 1 Meter in Godot.*
3.  Texturing: You can apply basic materials. Godot will try to import them.

## Step 2: Save directly to the Project
The magic of Godot 4 is that it reads `.blend` files directly!

1.  **Save As...** in Blender.
2.  Navigate to your `lunco-sim` folder.
3.  Save it inside a logical folder, e.g., `content/maps/MyCrater/my_crater.blend`.

## Step 3: Import in Godot
1.  Open the Godot Editor.
2.  Godot will detect the new file and automatically import it.
3.  Double-click `my_crater.blend` in the FileSystem dock.
4.  Godot will ask if you want to create a new inherited scene. Click **New Inherited Scene**.

## Step 4: Make it "Solid" (Collision)
By default, your mesh is a ghost; rovers will drive through it. Let's make it solid.

1.  In your new Scene, select the mesh node (the crater).
2.  In the top menu bar of the 3D viewport, look for a button called **Mesh**.
3.  Click **Mesh > Create Trimesh Static Body**.
4.  This creates a "StaticBody3D" with a collision shape matching your crater.

## Step 5: See it in the World
1.  Save your new scene (e.g., `my_crater_scene.tscn`).
2.  Open the main simulation scene or your test scene.
3.  Drag and drop `my_crater_scene.tscn` into the world.
4.  Press **Play** (F5).
5.  Drive your rover onto your new crater!

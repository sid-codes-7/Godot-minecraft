# Godot-minecraft
gdscript for Godot Minecraft 

#Three Main Nodes:

#World

-WorldEnviroment
-DirectionalLight3D
-Player
-GridMap
-MeshInstance3D (used for blocks)

#Player

-CollisionShape3D
-MeshInstance3D
-Camera3D
  -RayCast3D (used to handle the player and its POV to place blocks in any direction)

#Blocks

-Bricks_Grey
  -StaticBody3D
    -CollisionShape3D
 
-Dirt
  -StaticBody3D
    -CollisionShape3D
    
-Leaves
  -StaticBody3D
    -CollisionShape3D
    
-Grass
  -StaticBody3D
    -CollisionShape3D
    
-Stone
  -StaticBody3D
    -CollisionShape3D
    
-Wood
  -StaticBody3D
    -CollisionShape3D
    
-WoodPlanks
  -StaticBody3D
    -CollisionShape3D

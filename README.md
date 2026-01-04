# Godot Minecraft

GDScript project for a Minecraft-style game built in Godot.

---

## Three Main Nodes
---------
### World
---------
- WorldEnvironment
- DirectionalLight3D
- Player
- GridMap
- MeshInstance3D (used for blocks)
---------
### Player
---------
- CollisionShape3D
- MeshInstance3D
- Camera3D  
  - RayCast3D (used to handle the player POV and place blocks in any direction)
- Hotbar  
---------
### Blocks
---------
#### Bricks_Grey
- StaticBody3D  
  - CollisionShape3D

#### Dirt
- StaticBody3D  
  - CollisionShape3D

#### Leaves
- StaticBody3D  
  - CollisionShape3D

#### Grass
- StaticBody3D  
  - CollisionShape3D

#### Stone
- StaticBody3D  
  - CollisionShape3D

#### Wood
- StaticBody3D  
  - CollisionShape3D

#### WoodPlanks
- StaticBody3D  
  - CollisionShape3D

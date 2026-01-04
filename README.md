# 🧱 Godot Minecraft

A **GDScript-based project** for a **Minecraft-style sandbox game** built with the **Godot Engine**.  
This project focuses on block placement, player interaction, and a simple world structure.

---

## 📁 Project Structure

The game is organized around **three main node groups**:

- **World**
- **Player**
- **Blocks**

---

## 🌍 World

The `World` node manages the environment, lighting, terrain, and main menu UI.

### Nodes
- `WorldEnvironment`
- `DirectionalLight3D`
- `Player`
- `GridMap` – Used for block placement
- `Sea`

### Main Menu UI
- `VBoxContainer`
  - `NewGameButton`
  - `LoadButton`
  - `QuitButton`
<img width="319" height="159" alt="image" src="https://github.com/user-attachments/assets/8798c9cb-7fc0-406e-8248-d339e3486e30" />


### Camera
- `CameraPivot` – Rotates the camera around the map in the main menu
  - `Camera3D`
---

## 🧍 Player

The `Player` node handles movement, camera control, and block interaction.

### Nodes
- `CollisionShape3D`
- `MeshInstance3D`
- `Camera3D`
  - `RayCast3D` – Used for player POV and placing blocks in any direction
- `Hotbar`

---

## 🧱 Blocks

Each block type is implemented as a `StaticBody3D` with collision support.

### Block Types

#### Bricks_Grey
- `StaticBody3D`
  - `CollisionShape3D`

#### Dirt
- `StaticBody3D`
  - `CollisionShape3D`

#### Leaves
- `StaticBody3D`
  - `CollisionShape3D`

#### Grass
- `StaticBody3D`
  - `CollisionShape3D`

#### Stone
- `StaticBody3D`
  - `CollisionShape3D`

#### Wood
- `StaticBody3D`
  - `CollisionShape3D`

#### WoodPlanks
- `StaticBody3D`
  - `CollisionShape3D`
<img width="248" height="73" alt="image" src="https://github.com/user-attachments/assets/01dc7b50-7015-4f19-a6c0-7e092da5b1fc" />

---

## 🚀 Notes
- Built entirely using **GDScript**
- Designed for **block-based world interaction**
- Easily extendable with new block types, crafting systems, or terrain generation
<img width="775" height="449" alt="image" src="https://github.com/user-attachments/assets/d1c3ddc2-53f2-4483-a219-ec62f14c8d36" />

---



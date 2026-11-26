# This is a project for managing packages

# Project Setup

- [GitHub](GitHub.md)

- [ProjectSetup](ProjectSetup.md)

# Plugins

- Mesh Terrain Mode

| Plug In                | description |
|------------------------|-------------|
| Mesh Terrain Mode      |             |
| Mesh Partition Interop |             |
| Mesh Partition Water   |             |






























# This is a template for creating UE5 games

This includes some useful configurations, including...



### 1.3. Creating Custom Templates

1. [Creating Custom Templates](https://dev.epicgames.com/documentation/en-us/unreal-engine/converting-a-project-to-an-unreal-engine-template)

### 1.4. Do we need the contents of these folders

1. Intermediate
1. Binaries
1. \*.log

## 2. Customization

### 2.1. Displacement - nanite-tessellation

**Note:** Demo project already has this

[UE5 Nanite Tessellation](https://unrealstack.com/how-to-use-ue5-nanite-tessellation/)

1. [Material texture](https://www.youtube.com/watch?v=oRDmp0RLy7Q)
1. Open Config/DefaultEngine.ini
1. Go to [/Script/Engine.RendererSettings]

1. Add: r.Nanite.Tessellation=1
1. Add: r.Nanite.AllowTessellation=1

#### **Can be enabled or disabled in Console**

1. Enter: r.Nanite.Tessellation 1

#### **Enable Nanite in Landscape**

**NOTE:** Remember to enable Nanite in all your assets

[Nanite](https://dev.epicgames.com/documentation/en-us/unreal-engine/nanite-virtualized-geometry-in-unreal-engine)

## 3. Plugins

| Plug In                                 | description                 |
|-----------------------------------------|-----------------------------|
| Landscape Patch                         |                             |
| Text 3D                                 |                             |
| Water, Water Advanced                   |                             |
| Advanced Quest System                   |                             |
| Animation Locomotion Library            | For accurate foot placement |
| Modeling Tools Editor Mode              |                             |
| Procedural Content Generation Framework |                             |

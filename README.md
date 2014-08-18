Karts of Chaos - 3D Graphics
============================

3D modelling repository for the game [Karts of Chaos](https://github.com/kartsofchaos/game).

Cloning the repository
----------------------

This repository can both be cloned with [Git](http://git-scm.com/) or [Subversion](https://subversion.apache.org/).

Using Git:
- `git clone https://github.com/kartsofchaos/3d-graphics`
- [GUI clients](http://git-scm.com/downloads/guis)

Using Subversion:
- `svn checkout https://github.com/kartsofchaos/3d-graphics`
- [TortoiseSVN](http://tortoisesvn.net/)

Directory structure
-------------------

To facilitate the work for the person who will be adding the 3D-related work into Unity, the **finished** work should be copied into the appropriate root folder. Here is a brief explanation of the root folders:

- `animations` - Contains only **finished** animations.
- `models` - Contains only **finished** meshes.
- `personal/*` - Everyone has their own personal folder to store work-related data.
- `rigs` - Contains only **finished** rigs.
- `textures` - Contains only **finished** textures.

File formats
------------

The following file format should be followed:

- Exported 3D files - `.fbx`
- Exported textures - `.png` with size `2048x2048`

Naming convention
-----------------

The naming convention to follow are [CamelCase](http://en.wikipedia.org/wiki/CamelCase). This means that each next word or phrase should begin with a capital letter, and the spaces are left out, for example: `ThisIsATexture.png` or `IAmAnExportedObject.fbx`. 

An object should have an unique and descriptive name which consists of several segments. Below is a simple guide to name your `object`. Read each line, in this order, and does the question fit your object, add it to the filename:

- If the `object` is a component of another object, what `Type` is **that** object? If _not_, what `Type` is **this** object?
- If the `object` is a component of another object, what is **this** `Component` called?
- If the `object` has a name, what is **this** `Name`?
- If the `object` has a special property, what is **this** `Property` called?
- If the `object` has multiple variations of materials, what `Material` is **this**?
- If the `object` has multiple variations of sizes, what `Size` is **this**?

Model examples:
- `FencePoleWood.fbx` - It is a part of a `Fence`. It is a component `Pole`. It has the material `Wood`.
- `CreateMedium.fbx` - It is a `Create`. It has the size `Medium`.
- `CreateMetalSmall.fbx` - It is a `Create`. It has the material `Metal`. It has the size `Small`.
- `HouseCorner.fbx` - It is a `House`. It has the name `Corner`.
- `PlankBrokenLong.fbx` - It is a `Plank`. It is `Broken`. It has the size `Long`.

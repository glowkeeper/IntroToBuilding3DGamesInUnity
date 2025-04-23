# An Introduction to Building 3D Games in Unity

Welcome to _An Introduction to Building 3D Games in Unity_, a 3-hour workshop run for foundation year students at the [University of Roehampton](https://www.roehampton.ac.uk/).

## Table of Contents

- [An Introduction to Building 3D Games in Unity](#an-introduction-to-building-3d-games-in-unity)
  - [Table of Contents](#table-of-contents)
  - [Introduction to Building 3D Games in Unity](#introduction-to-building-3d-games-in-unity)
  - [Dependencies](#dependencies)
  - [Workshop Contents](#workshop-contents)
  - [Background Material](#background-material)
  - [License](#license)

## Introduction to Building 3D Games in Unity

The workshop is an introduction to building 3D games, using [Unity](https://unity.com/). 

During the workshop, you will use [meshes](https://en.wikipedia.org/wiki/Polygon_mesh) to define the shape of objects in your virtual world, which you will define with [materials](https://docs.unity3d.com/Manual/Materials.html) and [textures](https://docs.unity3d.com/Manual/Textures.html). You will also simulate real-world forces, such as gravity and collisions, using physics components, such as [rigidbodies](https://en.wikipedia.org/wiki/Rigid_body) and [colliders](https://docs.unity3d.com/Manual/CollidersOverview.html). You will add some [audio](https://docs.unity3d.com/Manual/AudioOverview.html), and, to add a game element to that world, you will do some [scripting](https://docs.unity3d.com/Manual/ScriptingSection.html).

## Dependencies

You should sign up to the free [Unity Student plan](https://unity.com/products/unity-student). Without that plan, you will be unable to sign into the [Unity Hub](https://unity.com/unity-hub) on the Macs in DB081. And if you cannot sign into the Unity Hub, you will be unable to take part in the workshop.

If you plan on taking part in the workshop via your own laptop in your own time, you should install [Unity 2022.3.57](https://unity.com/releases/editor/whats-new/2022.3.57), via the Unity Hub. You will also need [Visual Studio](https://visualstudio.microsoft.com/) for the scripting part of the workshop; so if you do not have that installed already, you should add Visual Studio as a module when you install Unity.

## Workshop Contents

- [Editor Overview](./docs/editorOverview.md)
- [Creating 3D Objects](./docs/creating3DObjects.md)
- [Adding Input Controls](./docs/addingInputControls.md)

Below is some background material to the concepts introduced above:

- [Modelling](./modelling.md)
- [Materials and Textures](./materials.md)
- [3D Physics](./3DPhysics.md)
- [Audio](./audio.md)
- [Scripting](./scripting.md)

## Background Material

As you immerse yourself in the 3D programming space, you may wish to deepen your knowledge by grasping some of the theoretical background underpinning the work you do. To help get you started, here's some theory:

- [Graphics Background](./docs/supplimentary/graphicsBackground.md)
- [Coordinate Systems](./docs/coordinateSystems.md)
- [Vectors](./docs/vectors.md)
- [Trigonometry](./docs/trigonometry.md)
- [Forces](./docs/forces.md)

Much of the naterial for the documents above was collated from [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html), the [3D Maths Primer for Graphics and Game Development](https://gamemath.com/), and [The Nature of Code](https://natureofcode.com/) - if you're interested in grasping more of the theory, then go investigate those sites. [The Nature of Code](https://natureofcode.com/) uses a Javascript library called [p5.js](https://p5js.org/) to demonstrate its principles, but don't worry too much if you're not familiar with javascript, as you do not necessarily need that familiarity to understand the concepts presented.

## License

[MIT License](LICENSE).

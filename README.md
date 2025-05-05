# An Introduction to Building 3D Games in Unity

Welcome to _An Introduction to Building 3D Games in Unity_. 

The documentation here form the materials for a 3-hour workshop run for foundation year students at the [University of Roehampton](https://www.roehampton.ac.uk/).

## Table of Contents
<!-- no toc -->
- [Introduction to Building 3D Games in Unity](#introduction-to-building-3d-games-in-unity)
- [Dependencies](#dependencies)
- [Workshop Contents](#workshop-contents)
- [Background Material](#background-material)
- [License](#license)

## Introduction to Building 3D Games in Unity

The workshop is an introduction to building 3D games, using [Unity](https://unity.com/). 

During the workshop, you will place objects in a virtual space, which you will colour, using [materials](https://docs.unity3d.com/Manual/Materials.html). You will also simulate real-world forces, such as gravity and collisions, using physics components, such as [rigidbodies](https://en.wikipedia.org/wiki/Rigid_body) and [colliders](https://docs.unity3d.com/Manual/CollidersOverview.html). Finally, you will create a game by adding some user input and by doing some [scripting](https://docs.unity3d.com/Manual/ScriptingSection.html).

## Dependencies

You should sign up to the free [Unity Student plan](https://unity.com/products/unity-student). Without that plan, you will be unable to sign into the [Unity Hub](https://unity.com/unity-hub) on the Macs in DB081. And if you cannot sign into the Unity Hub, you will be unable to take part in the workshop.

If you plan on taking part in the workshop via your own laptop in your own time, you should install [Unity 2022.3.57](https://unity.com/releases/editor/whats-new/2022.3.57), via the Unity Hub. You will also need [Visual Studio](https://visualstudio.microsoft.com/) for the scripting part of the workshop; so if you do not have that installed already, you should add Visual Studio as a module when you install Unity.

## Workshop Contents

- [Editor Overview](./docs/editorOverview.md)
- [Creating 3D Objects](./docs/creating3DObjects.md)
- [Adding Input Controls](./docs/addingInputControls.md)
- [Creating the Game](./docs/creatingTheGame.md)

## Background Material

Below is some background material that helps explain some of the concepts introduced above:

- [Modelling](./docs/supplimentary/modelling.md)
- [Materials and Textures](/docs/supplimentary/materials.md)
- [3D Physics](/docs/supplimentary/3DPhysics.md)
- [Scripting](/docs/supplimentary/scripting.md)

As you immerse yourself in the 3D programming space, you may wish to deepen your knowledge by grasping some of the theoretical background underpinning the work you do. To help get you started, here's some theory:

- [Graphics Background](./docs/supplimentary/graphicsBackground.md)
- [Coordinate Systems](./docs/supplimentary/maths/coordinateSystems.md)
- [Vectors](./docs/supplimentary/maths/vectors.md)
- [Trigonometry](./docs/supplimentary/maths/trigonometry.md)
- [Forces](./docs/forces.md)

Much of the naterial for the documents above was collated from [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html), the [3D Maths Primer for Graphics and Game Development](https://gamemath.com/), and [The Nature of Code](https://natureofcode.com/) - if you're interested in grasping more of the theory, then go investigate those sites. [The Nature of Code](https://natureofcode.com/) uses a Javascript library called [p5.js](https://p5js.org/) to demonstrate its principles, but don't worry too much if you're not familiar with javascript, as you do not necessarily need that familiarity to understand the concepts presented.

## License

[MIT License](LICENSE).

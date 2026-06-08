# Awesome Game Physics [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support)
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome)
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of game physics engines, simulation frameworks, collision detection libraries, educational resources, research papers, and tools for physics-based game development.

Game physics powers realistic and interactive virtual worlds by simulating motion, collisions, forces, fluids, soft bodies, destruction, and other physical phenomena. Whether building arcade-style games or highly realistic simulations, game physics is a fundamental discipline in modern game development.

This list is intended for game developers, simulation engineers, graphics programmers, researchers, students, technical artists, and anyone interested in real-time physics simulation.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Physics Engines](#physics-engines)
- [Collision Detection](#collision-detection)
- [Rigid Body Simulation](#rigid-body-simulation)
- [Soft Body & Cloth Simulation](#soft-body--cloth-simulation)
- [Fluid & Particle Simulation](#fluid--particle-simulation)
- [Game Engine Physics Systems](#game-engine-physics-systems)
- [Physics Programming Libraries](#physics-programming-libraries)
- [Research & Academic Resources](#research--academic-resources)
- [Learning Resources](#learning-resources)
- [Communities](#communities)
- [Related Awesome Lists](#related-awesome-lists)

## Physics Engines

General-purpose physics engines for games and simulations.

- [Bullet Physics](https://bulletphysics.org/) — Open-source real-time collision detection and physics simulation library.
- [PhysX](https://developer.nvidia.com/physx-sdk) — NVIDIA's real-time physics simulation engine.
- [Jolt Physics](https://github.com/jrouwe/JoltPhysics) — Modern open-source rigid body physics engine.
- [ODE (Open Dynamics Engine)](https://www.ode.org/) — Open-source rigid body dynamics engine.
- [Newton Dynamics](https://github.com/MADEAPPS/newton-dynamics) — Real-time physics simulation engine.
- [ReactPhysics3D](https://www.reactphysics3d.com/) — Lightweight open-source 3D physics engine.
- [Project Chrono](https://projectchrono.org/) — Multi-physics simulation engine for advanced applications.

## Collision Detection

Libraries and frameworks focused on collision detection and spatial queries.

- [Box2D](https://box2d.org/) — Widely used 2D physics and collision detection engine.
- [FCL](https://github.com/flexible-collision-library/fcl) — Flexible Collision Library for proximity queries.
- [libccd](https://github.com/danfis/libccd) — Library for continuous collision detection.
- [Opcode](https://github.com/Pierre-Terdiman/Opcode) — Optimized collision detection library.
- [Embree](https://www.embree.org/) — High-performance ray tracing kernels useful for physics and collision systems.
- [NanoRT](https://github.com/lighttransport/nanort) — Lightweight ray tracing acceleration library.

## Rigid Body Simulation

Libraries and systems specializing in rigid body dynamics.

- [Bullet Rigid Body System](https://bulletphysics.org/) — Rigid body simulation and constraints.
- [PhysX Rigid Bodies](https://developer.nvidia.com/physx-sdk) — High-performance rigid body physics.
- [Jolt Physics](https://github.com/jrouwe/JoltPhysics) — Modern rigid body simulation framework.
- [MuJoCo](https://mujoco.org/) — Physics engine designed for robotics and control simulation.
- [DART](https://dartsim.github.io/) — Dynamic Animation and Robotics Toolkit.
- [RaiSim](https://raisim.com/) — Physics engine focused on robotics and simulation.

## Soft Body & Cloth Simulation

Tools and frameworks for deformable objects and cloth simulation.

- [NVIDIA Flex](https://developer.nvidia.com/flex) — Unified particle-based simulation framework.
- [SOFA Framework](https://www.sofa-framework.org/) — Open-source framework for physical simulation.
- [Bullet Soft Body](https://bulletphysics.org/) — Soft body simulation module.
- [Position Based Dynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics) — Library implementing position-based simulation methods.
- [ArcSim](https://github.com/cmu-graphics/arcsim) — Cloth simulation system.
- [C-IPC](https://github.com/ipc-sim/C-IPC) — Collision-aware deformable simulation framework.

## Fluid & Particle Simulation

Frameworks and tools for fluids, particles, smoke, and related effects.

- [NVIDIA Flow](https://developer.nvidia.com/flow) — Real-time fluid simulation technology.
- [Mantaflow](https://mantaflow.com/) — Fluid simulation framework used in Blender.
- [Taichi](https://www.taichi-lang.org/) — High-performance simulation programming language.
- [SPHinXsys](https://www.sphinxsys.org/) — Smoothed Particle Hydrodynamics simulation framework.
- [DualSPHysics](https://dual.sphysics.org/) — Open-source particle-based fluid simulation.
- [OpenFOAM](https://www.openfoam.com/) — Computational fluid dynamics platform.

## Game Engine Physics Systems

Physics systems built into major game engines.

- [Unity Physics](https://unity.com/) — Physics system integrated into Unity.
- [Unity DOTS Physics](https://unity.com/dots) — Data-oriented physics system for Unity.
- [Unreal Engine Physics](https://www.unrealengine.com/) — Integrated physics framework for Unreal Engine.
- [Chaos Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/chaos-physics-overview) — Unreal Engine's advanced physics system.
- [Godot Physics](https://godotengine.org/) — Integrated 2D and 3D physics engine.
- [CryEngine Physics](https://www.cryengine.com/) — Physics system integrated into CryEngine.

## Physics Programming Libraries

Libraries and tools useful for implementing custom physics systems.

- [GLM](https://github.com/g-truc/glm) — Mathematics library for graphics and physics programming.
- [Eigen](https://eigen.tuxfamily.org/) — High-performance linear algebra library.
- [CGAL](https://www.cgal.org/) — Computational geometry algorithms library.
- [Boost.Geometry](https://www.boost.org/doc/libs/release/libs/geometry/) — Geometry algorithms library.
- [MathFu](https://github.com/google/mathfu) — Math library for games and simulations.
- [TinyXML2](https://github.com/leethomason/tinyxml2) — Lightweight XML parser often used in simulation projects.

## Research & Academic Resources

Research institutions, papers, and academic resources related to physics simulation.

- [SIGGRAPH](https://www.siggraph.org/) — Leading conference for computer graphics and simulation.
- [Eurographics](https://www.eg.org/) — European computer graphics association.
- [ACM Digital Library](https://dl.acm.org/) — Research papers covering simulation and game physics.
- [arXiv Computer Graphics](https://arxiv.org/archive/cs) — Open-access research papers.
- [Physics-Based Animation Course Notes](https://www.cs.cmu.edu/~baraff/sigcourse/) — Foundational simulation references.
- [Interactive Computer Graphics Group](https://interactive-graphics.de/) — Research in simulation and animation.

## Learning Resources

Books, tutorials, courses, and educational resources.

- [Game Physics Engine Development](https://www.crcpress.com/Game-Physics-Engine-Development/Millington/p/book/9780123819765) — Comprehensive book on building physics engines.
- [Physics for Game Developers](https://www.oreilly.com/library/view/physics-for-game/9781491905791/) — Practical introduction to game physics.
- [Real-Time Collision Detection](https://realtimecollisiondetection.net/) — Foundational collision detection reference.
- [Game Programming Patterns](https://gameprogrammingpatterns.com/) — Design patterns relevant to simulation systems.
- [Catlike Coding Physics Tutorials](https://catlikecoding.com/) — Unity-focused physics tutorials.
- [LearnOpenGL](https://learnopengl.com/) — Graphics programming tutorials useful for simulation developers.

## Communities

Communities and organizations supporting game physics development.

- [GameDev.net](https://www.gamedev.net/) — Community for game developers.
- [r/gamedev](https://www.reddit.com/r/gamedev/) — Game development community.
- [Game Developer](https://www.gamedeveloper.com/) — Articles and resources for game development.
- [SIGGRAPH Community](https://www.siggraph.org/) — Graphics and simulation professionals.
- [Godot Community](https://godotengine.org/community) — Open-source game development community.
- [Unity Community](https://unity.com/community) — Community for Unity developers.

## Related Awesome Lists

- [Awesome Game Engines](https://github.com/brandonhimpfen/awesome-game-engines) — Game engines, frameworks, tools, and resources for game development.
- [Awesome Mathematics](https://github.com/brandonhimpfen/awesome-mathematics) — Resources for pure, applied, and computational mathematics.
- [Awesome Computational Mathematics](https://github.com/brandonhimpfen/awesome-computational-mathematics) — Tools, frameworks, and educational resources for computational mathematics.
- [Awesome Robotics](https://github.com/brandonhimpfen/awesome-robotics) — Tools, frameworks, libraries, and resources for robotics.
- [Awesome Computer Vision](https://github.com/brandonhimpfen/awesome-computer-vision) — Resources for computer vision and visual computing.
- [Awesome AI](https://github.com/brandonhimpfen/awesome-ai) — Resources, libraries, and tools for artificial intelligence.
- [Awesome Game Development](https://github.com/brandonhimpfen/awesome-game-development) — Tools, frameworks, and resources for game development.
- [Awesome Aerospace Engineering](https://github.com/brandonhimpfen/awesome-aerospace-engineering) — Resources and tools for aerospace engineering and simulation.
- [Awesome Mechanical Engineering](https://github.com/brandonhimpfen/awesome-mechanical-engineering) — Resources and tools for mechanics and simulation.
- [Awesome Physics](https://github.com/brandonhimpfen/awesome-physics) — Resources for physics research and education.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

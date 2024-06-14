# Simulation
* ロボットを事前にテストしたり、改善したりすることができます。
* OpenSourceとして公開されて提供している物もあります。
* 直接、作る事も可能です。(数学と科学の知識が必要です。)

```mermaid
flowchart LR
    subgraph Industrials
        SolidWorks
        AutoCAD
        Fusion360
        Inventor
    end
    
    subgraph Physics Engins 
        Warp
        PhysX4
        PhysX5
        Flow
        Flex
        Blast
    end
    click warp 'https://github.com/NVIDIA/warp'

```
## Real-time physics engines
### Open source
* Advanced Simulation Library - open source hardware accelerated multiphysics simulation software
* Box2D
* Bullet
* Chipmunk physics engine - 2D physics engine
* Jolt Physics - Horizon Forbidden West physics engine
* Newton Game Dynamics
* Open Dynamics Engine
* PAL (Physics Abstraction Layer) - A uniform API that supports multiple physics engines
* PhysX
* Project Chrono - An open source simulation engine for multi-physics applications.
* Siconos Modeling and the simulation of mechanical systems with contact, impact and Coulomb's friction
* SOFA (Simulation Open Framework Architecture)
* Tokamak physics engine

### Closed source/limited free distribution
* Digital Molecular Matter
* Havok
* Chaos by Epic Games
* Vortex by CMLabs Simulations
* AGX Multiphysics by Algoryx Simulation AB
* Algodoo by Algoryx Simulation AB
* Rubikon by Valve Corporation
* High precision physics engines
* VisSim - Visual Simulation engine for linear and nonlinear dynamics

## Flexibilities and Expandable Engine
* Component
* Server, Client Programming
* AI, Control Programming
* Cross Devices
* Compatibilities
* Variations
* Realtime Programmable and Controllable System
* User Interface
* Publishing
```mermaid
flowchart LR
    subgraph WEB
        TJ(three.js)
        BB(Babylon.js)
    end
    
    subgraph Game Engines 
        UN(Unity)
        UE(Unreal Engine)
    end

```


## IDE
```mermaid
flowchart LR
    subgraph Libraries 
        img(imgui)
    end
    subgraph Graphics Libraries
        OG(OpenGL)
        OC(OpenCL)
        VC(Vulkan)
        DX(DirectX)
    end
    subgraph Hardware and Driver
        NV(NVIDIA)
        AMD(AMD)
    end
    subgraph Tools 
        VS(Visual Studio)
        CM(CMAKE)
        PC(PyCharm)
        VSCODE(Visual Studio CODE)
    end

```
# Game Programming Resources
My personal list of reference resources for game programming

# Table of Contents
* [AI](#ai)
* [Graphics](#graphics)
  * [Hardware and Graphics Pipeline](#hardware-and-graphics-pipeline)
  * [API specifics](#api-specifics)
  * [Shader Programming](#shader-programming)
  * [Techniques](#techniques) 
  * [Graphics studies](#graphics-studies)
* [Low Level Programming](#low-level-programming)
  * [Assembly and CPU microarchitecture](#assembly-and-cpu-microarchitecture)
  * [SIMD](#simd)
* [Programming Languages](#programming-languages)
* [Math](#math)
* [Networking](#networking)
* [Multithreading](#multithreading)
* [Physics](#physics)
* [Software architecture and design](#software-architecture-and-design)
  * [Design Patterns and OOP](#design-patterns-and-oop)
  * [Entity-component-systems (ECS)](#entity-component-system)
  * [Data Oriented Design](#data-oriented-design)

## AI
* [Introduction to A* - Red Blob Games](https://www.redblobgames.com/pathfinding/a-star/introduction.html)
* [Implementation of A* - Red Blob Games](https://www.redblobgames.com/pathfinding/a-star/implementation.html)
* [Pathfinding for Tower Defense - Red Blob Games](https://www.redblobgames.com/pathfinding/tower-defense/)
* [Relic's Templatized A* implementation](http://jurneydownloads.s3.amazonaws.com/gdc/Relic_AStarKit.zip)
* [Ellie: Buddy AI in The Last of Us - Game AI Pro 2](http://www.gameaipro.com/GameAIPro2/GameAIPro2_Chapter35_Ellie_Buddy_AI_in_The_Last_of_Us.pdf)

## Graphics
### Hardware and Graphics Pipeline
* [Render Hell book 1 - Overview](https://simonschreibt.de/gat/renderhell-book1/)
* [Render Hell book 2 - Pipeline](https://simonschreibt.de/gat/renderhell-book2/)
* [A trip through the Graphics Pipeline](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/)
* [Understanding modern GPU's part 1 - introduction](https://traxnet.wordpress.com/2011/07/16/understanding-modern-gpus-1/)
* [Understanding modern GPU's part 2 - Drivers and Command Ring](https://traxnet.wordpress.com/2011/07/18/understanding-modern-gpus-2/)
* [Understanding Modern GPU's part 3 - Command And Setup Logic](https://traxnet.wordpress.com/2011/07/22/understanding-modern-gpus-3/)
* [Scheduling the Graphics Pipeline - SIGGRAPH 2011](http://bps11.idav.ucdavis.edu/talks/05-schedulingGraphicsPipeline-BPS2011-ragankelley.pdf)
* [Breaking down barriers - part 1](https://mynameismjp.wordpress.com/2018/03/06/breaking-down-barriers-part-1-whats-a-barrier/)
* [Breaking down barriers - part 2](https://mynameismjp.wordpress.com/2018/04/01/breaking-down-barriers-part-2-synchronizing-gpu-threads/)
* [A look at the PowerVR graphics architecture: Tile-based rendering](https://www.imgtec.com/blog/a-look-at-the-powervr-graphics-architecture-tile-based-rendering/)
* [The Mali GPU: An Abstract Machine, Part 1 - Frame Pipelining](https://community.arm.com/graphics/b/blog/posts/the-mali-gpu-an-abstract-machine-part-1---frame-pipelining)
* [The Mali GPU: An Abstract Machine, Part 2 - Tile-based Rendering](https://www.community.arm.com/graphics/b/blog/posts/the-mali-gpu-an-abstract-machine-part-2---tile-based-rendering)
* [The Mali GPU: An Abstract Machine, Part 3 - The Midgard Shader Core](https://community.arm.com/graphics/b/blog/posts/the-mali-gpu-an-abstract-machine-part-3---the-midgard-shader-core)
* [The Mali GPU: An Abstract Machine, Part 4 - The Bifrost Shader Core](https://www.community.arm.com/graphics/b/blog/posts/the-mali-gpu-an-abstract-machine-part-4---the-bifrost-shader-core)
* [AMD GCN3 ISA Architecture Manual](https://gpuopen.com/compute-product/amd-gcn3-isa-architecture-manual/)

### API specifics
#### DirectX 12
* [Direct3D 12 Programming Guide](https://msdn.microsoft.com/en-us/library/windows/desktop/dn899121(v=vs.85).aspx)
* [Getting familiar with DX12](http://gsteph.blogspot.com.br/2015/02/directx12-getting-familiar-with-dx12.html)
* [Practical DirectX 12 – Programming Model and Hardware Capabilities - GDC 2016](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/Practical_DX12_Programming_Model_and_Hardware_Capabilities.pdf)
* [Right on Queue: Advanced DirectX 12 Programming - GDC 2016](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/GDC_2016_D3D12_Right_On_Queue_final.pdf)
* [D3D12 Shader Live-Reloading Introduction](https://nlguillemot.wordpress.com/2017/01/31/d3d12-shader-live-reloading/)
* [A Journey Through DirectX 12 Dynamic Memory Allocations](http://3dgep.blogspot.com.br/2016/02/a-journey-through-directx-12-dynamic.html?m=1)
* [Managing Descriptor Heaps in Direct3D12](https://www.codeproject.com/Articles/1180619/Managing-Descriptor-Heaps-in-Direct-D)
* [Implementing Dynamic Resources with Direct3D12](https://www.codeproject.com/Articles/1094799/Implementing-Dynamic-Resources-with-Direct-D)
#### OpenGL
* [Learn OpenGL](https://learnopengl.com/)
* [OpenGL Renderer Design - nlguillemot](https://nlguillemot.wordpress.com/)
* [Approaching Zero Driver Overhead on OpenGL](http://www.slideshare.net/CassEveritt/approaching-zero-driver-overhead)
#### Vulkan
* [Vulkan tutorial](https://vulkan-tutorial.com/)
* [Vulkan in 30 minutos](https://renderdoc.org/vulkan-in-30-minutes.html)
* [Vulkan Fast Paths - GDC 2016](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
* [Vulkan Multithreading](https://developer.nvidia.com/sites/default/files/akamai/gameworks/blog/munich/mschott_vulkan_multi_threading.pdf)

### Shader Programming
* [The book of Shaders](https://thebookofshaders.com/)
* [A gentle introduction to shaders in Unity3D](https://www.alanzucconi.com/2015/06/10/a-gentle-introduction-to-shaders-in-unity3d/)

### Techniques
* [Advances in Real-Time Rendering in 3D Graphics and Games](http://advances.realtimerendering.com/)
* [A quick overview of MSAA](https://mynameismjp.wordpress.com/2012/10/24/msaa-overview/)
* [Physically Based Shading in Theory and Practice - SIGGRAPH 2016](http://blog.selfshadow.com/publications/s2016-shading-course/)
* [Real-Time Many-Light Management and Shadows with Clustered Shading](https://newq.net/publications/more/s2015-many-lights-course)
* [Order your draw calls around!](http://realtimecollisiondetection.net/blog/?p=86)

### Graphics Studies
* [GTA V Graphics Study - Adrian Courreges](http://www.adriancourreges.com/blog/2015/11/02/gta-v-graphics-study/)
* [DOOM 2016 Graphics Study - Adrian Courreges](http://www.adriancourreges.com/blog/2016/09/09/doom-2016-graphics-study/)
* [Metal Gear Solid V - Graphics Study](http://www.adriancourreges.com/blog/2017/12/15/mgs-v-graphics-study/)
* [How Unreal renders a frame](https://interplayoflight.wordpress.com/2017/10/25/how-unreal-renders-a-frame/amp/)
* [The Rendering of Middle Earth Shadow of Mordor](http://www.elopezr.com/the-rendering-of-middle-earth-shadow-of-mordor/)

## Low Level Programming
### Assembly and CPU microarchitecture
* [Software optimization resources](http://www.agner.org/optimize/)
* [The microarchitecture of Intel, AMD and VIA CPUs](http://www.agner.org/optimize/microarchitecture.pdf)
* [Optimizing subroutines in assembly language: An optimization guide for x86 platforms](http://www.agner.org/optimize/optimizing_assembly.pdf)
### SIMD
* [SSE: mind the gap!](https://fgiesen.wordpress.com/2016/04/03/sse-mind-the-gap/)
* [SIMD at Insomniac Games](https://deplinenoise.files.wordpress.com/2015/03/gdc2015_afredriksson_simd.pdf)

## Programming Languages
### C++
* [Debugging Tips and Tricks for C++ in Visual Studio](https://blogs.msdn.microsoft.com/vcblog/2016/07/11/debugging-tips-and-tricks-for-c-in-visual-studio/)
* [Practical Guide to bare metal C++](https://arobenko.gitbooks.io/bare_metal_cpp/content/)
* [Simple Live C++ Reloading in Visual Studio](https://nlguillemot.wordpress.com/2018/02/16/simple-live-c-reloading-in-visual-studio/)

### C#
* [C# Yellow Book](http://www.csharpcourse.com/)

## Math
* [Building a better jump - Math for Game Programmers](http://www.mathforgameprogrammers.com/gdc2016/GDC2016_Pittman_Kyle_BuildingABetterJump.pdf)
* [Bezier Curves](https://javascript.info/bezier-curve)
* [Essential Math for Game Programmers](http://essentialmath.com/book.htm)
* [Grassman Algebra in Game Development - Eric Lengyel (GDC 2014)](http://www.terathon.com/gdc14_lengyel.pdf)
* [Math for Game Developers](https://www.youtube.com/watch?v=sKCF8A3XGxQ&list=PLW3Zl3wyJwWOpdhYedlD-yCB7WQoHf-My)
* [Math for Game Programmers](http://www.mathforgameprogrammers.com/)

## Multithreading
* [Designing the Framework of a
Parallel Game Engine ](https://software.intel.com/sites/default/files/Designing_a_Parallel_Game_Engine.pdf)
* [Destiny's Multithreaded Rendering Architecture](http://gdcvault.com/play/1021926/Destiny-s-Multithreaded-Rendering)
* [Multiprocessor Game Loops: Lessons from Uncharted 2: Among Thieves](https://www.slideshare.net/naughty_dog/multiprocessor-game-loops-lessons-from-uncharted-2-among-thieves)
* [Parallelizing the Naughty Dog Engine Using Fibers](http://www.gdcvault.com/play/1022186/Parallelizing-the-Naughty-Dog-Engine)
* [The Poor Man's Threading Architecture](http://etodd.io/2016/01/12/poor-mans-threading-architecture/)

## Networking
* [Beej's Guide to Network Programming](http://beej.us/guide/bgnet/)
* [Game Networking - Gaffer on Games](https://gafferongames.com/categories/game-networking/)
* [Networked Physics - Gaffer on Games](https://gafferongames.com/categories/networked-physics/)
* [Development and Deployment of Multiplayer Online Games](http://ithare.com/contents-of-development-and-deployment-of-massively-multiplayer-games-from-social-games-to-mmofps-with-stock-exchanges-in-between/)
* [I Shot You First: Networking the Gameplay of HALO: REACH](http://www.gdcvault.com/play/1014345/I-Shot-You-First-Networking)
* [Tribes Networking Model](http://gamedevs.org/uploads/tribes-networking-model.pdf)
* [The Poor Man's Netcode](http://etodd.io/2018/02/20/poor-mans-netcode/)

## Physics
* [Fix your timestep!](https://gafferongames.com/post/fix_your_timestep/)

## Software Architecture and Design
### Design Patterns and OOP
* [Single responsibility principle](https://en.wikipedia.org/wiki/Single_responsibility_principle)
* [Command - Game Programming Patterns](http://gameprogrammingpatterns.com/command.html)
* [Component - Game Programming Patterns](http://gameprogrammingpatterns.com/component.html)
* [Observer - Game Programming Patterns](http://gameprogrammingpatterns.com/observer.html)
* [Singleton - Game Programming Patterns](http://gameprogrammingpatterns.com/observer.html)
* [Service Locator - Game Programming Patterns](http://gameprogrammingpatterns.com/service-locator.html)
* [Event Queue - Game Programming Patterns](http://gameprogrammingpatterns.com/event-queue.html)
### Entity Component System
* [Entity Component Samples - sosolimited](https://github.com/sosolimited/Entity-Component-Samples)
* [What is an Entity Component System architecture for game development? - Richard Lord](http://www.richardlord.net/blog/ecs/what-is-an-entity-framework.html)
* [Understanding Component-Entity-Systems](https://www.gamedev.net/articles/programming/general-and-gameplay-programming/understanding-component-entity-systems-r3013/)
### Data Oriented Design
* [CppCon 2014: Mike Acton "Data-Oriented Design and C++"](https://www.youtube.com/watch?v=rX0ItVEVjHc)
* [Data-Oriented Design (Or Why You Might Be Shooting Yourself in The Foot With OOP)](http://gamesfromwithin.com/data-oriented-design)
* [Data Locality - Game Programming Patterns](http://gameprogrammingpatterns.com/data-locality.html)
* [CPU Cache and why you care - Scoot Meyers](https://vimeo.com/97337258)
* [Mike Acton's comments on Ogre's OgreNode.cpp](https://www.bounceapp.com/116414)
* [Pitfalls of Object Oriented Programming - revisited](https://docs.google.com/presentation/d/1ST3mZgxmxqlpCFkdDhtgw116MQdCr2Fax2yjd8Az6zM/edit#slide=id.p)
* [Practical Examples in Data Oriented Design - Bitsquid](https://docs.google.com/presentation/d/17Bzle0w6jz-1ndabrvC5MXUIQ5jme0M8xBF71oz-0Js/present?slide=id.i0)
* [Typical C++ bullshit - Mike Acton](https://macton.smugmug.com/Other/2008-07-15-by-Eye-Fi/n-xmKDH/i-Dd6xtNh)

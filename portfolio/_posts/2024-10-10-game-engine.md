---
layout: default
title:  "3D Game Engine"
tags: C++
---

OpenGL-based 3D game engine, with GLSL shaders (incl. real-time volumetric shadows), VRAM and memory allocator, resource management, asset loading and preprocessing, and client-server networking. Provides a deep layer of abstraction from hardware interaction up to an accessible Lua scripting interface, upon which 3D graphics applications can be constructed.

Undertaking this project gave me a strong understanding of C++ and its language features, as well as understanding the value and good execution of many areas of software development, including:

<ul>
<li>Object-oriented programming beyond toy scale, where - with thought - design patterns emerge naturally and where OOP can be a massively powerful tool for abstraction but also can obscure fast hardware interaction.</li>
<li>Proper build processs and development environments to facilitate scalable software - compiling and linking C++ with an assortment of libraries highlighted the importance of having a good build process.</li>
<li>Weighing up tradeoffs to produce software that is tailored for a given task and environment - for instance, how compressed should textures be? This is a VRAM & render time tradeoff that may be different for each system, requiring thought about what kind of hardware the engine is designed for.</li>
</ul>
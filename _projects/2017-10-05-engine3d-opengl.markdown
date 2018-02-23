---
layout: project
title:  "Engine3D - OpenGL"
date:   2017-10-05 12:30:00
author: Enrique Trilles
categories:
- project
img: engine3d_opengl.png
thumb: thumb02.jpg
tagged: C++, OpenGL, Lua, ImGUI, GLSL, Multithread
ytbvideo: warPDs94UhE
repo: https://drive.google.com/open?id=1qZKAjOBabDGUBdJOxORX7hFSUWnGX4CD

---

This was a project created using C++, OpenGL and other specific utility libraries. The objective was to build a simple, yet fully operational 3D graphics engine from zero. A fully customizable editor interface was added to the project, letting the user to tinker around with the different components implemented for the engine.

Features:
- Multithread: Renderer and logic updates are handled in different threads.
- Dynamic lightning using shadowmaps.
- Runtime editable: The interface allows the modification of almost all parameters of each object and material.
- Materials: The shaders for the material of this project accepts these mappings: Albedo, normals, specular and emissive.
- Dynamic postprocesses: Postprocess parameters can be edited at runtime, and can be enabled or disabled whenever desired.
- Customizable interface: Editor windows can be moved and edited freely.
- Scripted configuration: Core parameters of the project can be changed with a lua script.
- Chrome profiler: The engine has a profiler that creates a file that can be used by chrome tracer to check processess behavior and times. Programmers can use this profiler tools for their own needs.

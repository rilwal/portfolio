---
title: Renderer
slug: renderer
layout: project
tags: project
thumbnail: /img/renderer.webp

project_type: Grapghics Programming
credits: [{'what': 'Programming', 'who': 'Jason Light'}]
tools: ['C++', 'OpenGL']
duration: 1 month+ (WIP)

description: A 3D renderer using C++ and OpenGL with PBR support. It can draw many objects with very few draw calls.
categories: ["C++", "GL"]
---

## Idea
In order to learn more about the rendering pipeline, and graphics programming in general, I decided to attempt to write a renderer. I've recently enjoyed reading many papers from Siggraph's [Advances in Real-Time Rendering](https://www.advances.realtimerendering.com/) and [Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2020-shading-course/) courses, but I still don't have much practical experience writing rendering code in practice. The general idea is to create a renderer in which I can play around with rendering techniques which interest me.


## Plan
Because I didn't have a very clear idea how I wanted to structure the renderer, I only had a very rough plan. I decided it would be faster to iterate and see what works in practice, rather than creating a whole detailed plan, only to find it doesn't work in practice. That being said, I had some features I wanted to work on:

* Render many objects (100k+?) with good performance
* Support basic physically based shading
* Hot-reloading of shaders, and automatic UI for editing Uniforms in real-time
* As much as possible, use bindless OpenGL calls to reduce API overhead ([AZDO](https://github.com/potato3d/azdo) style)

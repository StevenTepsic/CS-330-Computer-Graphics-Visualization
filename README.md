# CS-330-Computer-Graphics-Visualization

How I Approach Designing Software

Decompose systems into single-responsibility components before writing any logic
Plan data structures (materials, lights) as iterable arrays/structs rather than hardcoded blocks
Prototype visually first, reference a real object, map it to primitives, then build
Extract repeated render patterns into helper functions to keep code clean and scalable

How I Approach Developing Programs

Start simple, layer complexity, basic shapes → textures → materials → lighting
Use data-driven patterns (struct arrays + loops) instead of duplicating code per instance
Iterate visually: place, compile, observe, adjust, especially for values like shininess and light position
Build architecture that stacks across milestones without requiring rewrites

How Computer Science Helps Me Reach My Goals

Graphics work made linear algebra concrete, transformation matrices and dot products with immediate visual feedback
GPU pipeline experience (GLSL, uniform bindings, texture slots) applies to Unity, Unreal, WebGL, and Vulkan workflows
System architecture patterns (dependency injection, memory management, separation of concerns) transfer directly to software engineering roles
Shipped a complete OpenGL app with custom shaders, texture blending, a 4-light Phong rig, and interactive camera, a project I can walk through in any interview

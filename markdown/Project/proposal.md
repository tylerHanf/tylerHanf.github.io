
# Proposal
### Idea - Procedural tree generation via L-Systems using OpenGL compute shaders
<font size="4"> The goal is to use OpenGL compute shaders to procedurally generate trees. My initial idea is to use L-Systems for the procedural generation. Since the challenge of this is unknown, there are options to add features as needed
such as including a GUI to alter generation parameters on the fly, 
enhance procedurally generated texture quality, and add real-time camera interactivity as desired. It would also be fun to test the power of the compute shaders by benchmarking the performance. This could be done by trying to generate many trees on the fly.
</font>
### Team Members 
<font size="4"> None </font>

### Project Components
- Using OpenGL with GLEW and GLFW
- A custom (very lightweight, possibly header-only) OpenGL library for creating/managing buffers, compiling shaders, etc.
- Shader code for basic lighting (maybe more advanced if time allows), polygon generation, and possibly procedural texturing
- Possibly a graphics math library that I have been working on, I may extend some features and use it (if not I'll use GLM)
- Possibly a UI using DearImGUI if time allows

### Timeline
- February 10th or so -> Render a 3D object to the screen using a basic OpenGL interface library for making buffers, compiling programs, and handling textures within the OpenGL system. This library should be sufficient to handle what is needed for the rest of the project.
- Midpoint Review -> Define the L-System and draw generated trees in 2D.
- April 1st -> Generate 3D trees with basic texturing
- Mid-April -> Implement GUI for changing tree generation parameters on the fly
- End of April -> Enhanced quality of trees, lighting, and maybe some camera work for orbiting around the scene. Another possibility is to mess around with generating a forest or something like that. The project should be done by this point.

### Final Presentation
This will be a powerpoint with snippets and possible videos demoing the project. 
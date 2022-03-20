

### Outliner
The menu on the right with list of objects is called Outliner




## Shading Mode


Down section: Shading Editor:

### Shading editor
Adding materials to objects?

Cand Add properties of material like 

- BaseColor
- Metallic
- Roughness (Roghness vs Glossiness)
- Emmission (how it gives light)
- Normals



### Render Engines
Material preview mode uses Eevee
Render mode uses Eevee or cycles

#### Eevee
Real time render engine. Fakes realistic reflections

Options:
- Ambient Occlussion. Depths of shadow
- Screen Space reflection. Tried to recalculate some reflections in materials
- Bloom. Calculates the emmissions of the object

#### Cycles
Uses raytracing to calculate the light bouncing and takes time to calculate


## Index:



### Adding objects
Press SHIFT A for the ADD menu

### Pie menu
Press SHIFT S

### Select Box
Press W to change the shape (box, point,circle etc.)


### Moving 3D cursor:
Shift + Mouse Right click. New objects will be added on that location


### Orthogonal view
From the top

### Smoothing object
Right click on selected object to Shade Smooth

### Viewport
The window with visible scene

Viewport modes:
- Wiframe mode
- Solid mode
- Material Preview mode. White is default material if there none assigned. Uses Eevee engine
- Render mode. Materials and Light


### Camera View
Press 0

Press N to get camera toolbar -> View -> Check Camera to View, to lock the viewport 


### Frame Selected
Focuses on active object:
View -> Frame Selected




### Rendering 
Click on Render tab

It takes a lot of samples -> speed up go to scene options
Select Cycles and change Device to GPU Compute

If GPU is greyed out, Go to Edit -> Preferences -> system -> Cuda and Optix


#### Sampling
Viewport and Render Sampling
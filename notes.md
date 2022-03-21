

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



### Duplicate object
SHIFT  D


### Mirror Modifier (Wrench logo)
Can be added only to one object at a time. Pick the object that would be the axis of the mirror (as items can be mirrored on the central point of some other object)

### Copying data between objects
CONTROL L

Select Active object and Orange objects. Then control L to copy data, for example modifiers

Copies data from active object(yellow highlight) to Selected object (orange highlight)


### Edit Mode

Modyfing meshes. Mesh is highlighted in orange-ish. We can pick between selecting vertices, edges and planes.

Toggle Between Object and Edit mode clicking Tab

3 modes:

 - vertex mode
 - edge mode
 - face mode


Activities:

#### Extrude

When face selected, press E to extrude the region

#### Loop cut
CRTL R


#### Inset
Press I 


### Local View
View -> Local View -> Toggle Local View

Shows only the active object


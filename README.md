# QoL_Blender
Some Quality of Life add-ons for Blender. These are developed using Blender Python API and includes a bunch of tools - Visualization Tools, Interface Tools, Edge Wear Generator

## 1. Lumi Tools and Visualization Tools
<!-- Adding an image -->
<p align="center">
  <img src="/Images/LumiTools%231.png" width="204" title="Lumi Tools Interface"> 
</p>

### Lumi Tools:
The user interface is simple to understand and provides explanation of every option by hovering over it. It presents the following options:
1. **Clear Scene (Deep Clean):** Used to completely wipe the scene, including collections, nodes and everything present.
2. **Apply Modifiers:** Used to apply all the modifiers (Except armature) on selected objects.
3. **Delete Modifiers:** Used to delete all the modifiers on selected objects.
4. **Add Asset Library:** Add any asset library to Blender (Works only for 3.0.0+ releases of Blender). You can use this option to add any asset library without going to Edit>Preferences manually.
5. **Install Addon (Experimental):** This is still an experimental feature. This is used to install addons without installing then manually activating the respective add-on.
6. **Mark Asset(s):** Mark the selected objects as assets in the asset browser.
7. **Clear Asset(s):** Remove assets for selected objects from the asset browser.
8. **Purge:** This is an inbuilt command you can run to clear existing data. This includes data from geometry, materials, textures, that was deleted. Even after being deleted the data is still present in the until you close it. This option clears that cache and helps reduce memory usage.

### Visualization Tools:
1. **Visualization Materials:** This contains a list of pre-made materials that use Geometry Nodes _(Only work in 3.0.0 and above)_ and the Shader Editor to visualize objects in different ways. A list of materials is given below:
   - Ambient Occlusion
   - Depth
   - Direction _(For Hair Cards)_
   - Flow _(For Hair Cards)_
   - Normal Map
   - Opacity Map
   - Random Color
   - Random ID
   - Root _(For Hair Cards)_

<!-- Adding an image -->
<p align="center">
  <img src="/Images/Viz%231.png" width="204" title="Viz Tools Object Materials"> 
</p>

2. **Quick World:** This contains a list of pre-made materials that can be used to change the type of world that is used for rendering/look-dev. There are a bunch of presets based on your needs:
   - Blank
   - Black
   - Gray
   - White
   - Normal

<!-- Adding an image -->
<p align="center">
  <img src="/Images/Viz%232.png" width="204" title="Viz Tools World Materials"> 
</p>

Additionally you can also switch between **_Cycles and Eevee_**. You can also do so manually but using this tool enables some needed settings in the render settings. 

## 2. Edge Wear Generator:
This tool is used to generate edge wear on any given mesh. This uses Geometry nodes for generating the edge wear _(Only work in 3.0.0 and above)_. The settings are self explanatory and will give you results based on what you want to require. 

<!-- Adding an image -->
<p align="center">
  <img src="/Images/EdgeWear%231.png" width="204" title="Viz Tools World Materials"> 
</p>

There are a lot more tools and features coming up in the near future so stay tuned :)

### NOTE : This is an open repository and you can use/modify the tools as you want. Please give due credit where necessary.

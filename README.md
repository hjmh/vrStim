# vrStim: Generation of textures used in fly virtual reality

**generatePanoramas.ipynb** is used to generate 2D textures for panoramas that can be used in "1D" virtual reality experiments. Textures will be  saved in a "panoramas" subfolder.

**rescalePanoramas.ipynb** can be used to rescale images based on a measured projector "greyscale transfer function" (i.e. how image brightness relates to stimulus brightness). This can help with compensating for a non-linear translation of image to stimulus brightness.

**skyboxDesign.ipynb** is used to generate grey-scale versions from 3-color (RGB) skybox images. 

To generate skybox textures from Blender scenes, use [this code](https://github.com/JaneliaSciComp/blender-spherical-video) which allows you to make a cube map or movies through the scene, or use a python script and [Blender sky model](https://docs.blender.org/manual/en/latest/render/shader_nodes/textures/sky.html) to generate naturalistic sky textures.

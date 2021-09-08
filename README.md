# vrStim
Generation of visual stimuli used in fly virtual reality

**generatePanoramas.ipynb** is used to generate 2D textures for panoramas that can be used in "1D" virtual reality experiments. Textures will be  saved in a "panoramas" subfolder.

**rescalePanoramas.ipynb** can be used to rescale images based on a measured projector "greyscale transfer function" (i.e. how image brightness relates to stimulus brightness). This can help with compensating for a non-linear translation of image to stimulus brightness.

**skyboxDesign.ipynb** is used to generate grey-scale versions from 3-color (RGB) skybox images. 

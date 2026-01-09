# Random-Colors-Shader
Using p5js and glsl I created a shader that rounds the brightness of each pixel, uses the rounded brightness to pick from pre-chosen colors and then uses the actual brightness to fade between them using linear interpolation. 

# View Project on the Web
## Instructions
- **Click** once on the canvas to activate keyboard controls
- Press any key to change the color palette
  - **1** → mostly red hues  
  - **2** → mostly green  
  - **3** → mostly blue  
  - **Any other key** → return to randomized palettes

## Links
- View project: **link goes here**

# Features
## Quantized Color Mapping
- Reads brightness of every pixel
- **Rounds brightness** into discrete steps
- Uses rounded values to map to a limited palette of random colors

## Smooth Color Interpolation
- Actual brightness is used as a weight
- Shader fades between colors using **linear interpolation**
- Produces stylized posterization instead of harsh edges

# Code Structure
Single p5.js sketch paired with a compact GLSL fragment shader.  
Brightness sampling, rounding, and interpolation all handled in-shader.

# Purpose
Explore palette-driven rendering, color quantization, and real-time shader effects in a lightweight creative coding project.

# Technologies
- p5.js  
- WebGL / GLSL

# Graphics Pipeline
From geometry to pixels

## Rasterization
converting triangles to painted pixels
- for each triangle, which pixels are painted? how do we ensure that there is no gap between adjacent triangles? how do we decide the color of the pixel for two adjacent triangles?
- how do we interpolate the color (properities, UV) in screen space to take into account the perspective projection?
- how do we clip triangles that are only partially visible by the camera?
- vertex shader, fragment shader
- depth buffer
- Culling Strategies:
    - view culling 
    - occlusion culling
    - backface culling
    
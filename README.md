# VertexTracer
This is open source raytracer project that allows user to render quite realistically-looking scenes. It supports several light sources (directional, point), supports various materials (opaque, reflective refractive – Fresnel's equation). In addition, it has various antyaliasing methods (removing the jagged edges), and rendering is done using multithreading.

The newest features (may be **unstable**) will be pushed to **develop** branch and **stable** version of the engine will always be pushed to **master** branch. 

## TODOs
- [x] Tonemapping - auto-exposure
- [x] Light intensity calculated from AS
- [ ] Ambient light calculated from AS
- [ ] AS + fog
- [ ] Calculate AS coefficients at fly (for a fog)

### Dependencies' versions
- stb_image
- Assimp 3.2
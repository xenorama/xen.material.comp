# xen.material.comp

* translate jit.gl.material shaders in JitterGL3 to GLSL-shaders for jit.gl.shader
* optimize the native jit.gl.material normalmap-calculation from heightmap texture using the fragment shader

## optimization of shader GLSL-code yet to be achieved

* avoid occasional linear glitches across normalmap
* inherit texture dimensions in GL3 for precise mapping
* modulate material colors natively available in jit.gl.material in the shader code

__ any support and improvements welcome.

Tim H. / Xenorama

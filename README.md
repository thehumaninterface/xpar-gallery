## Gotchas along the Blender-GLTF-ThreeJS Pipeline

1. Blender text objects don't render. I suspect it's because text objects are not meshes.
Solution: Convert text to mesh
2. Blender is Z up, Three.js is Y up. Blender -Y = Three -Z. 
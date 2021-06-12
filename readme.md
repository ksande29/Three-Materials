# Three.js Journey - Materials Lesson
This lesson teaches about various materials that can be used with THREE.js. When you run the code, it is set to show three shapes that are reflecting lieka mirror. You can adjust the metalness and the roughness of the material using the debugger.
You can also change the ambient occlusion and displacement scale if you comment out line 92:
  material.envMap = environmentMapTexture
And uncomment out lines 93 to 103:
/*material.map = doorColorTexture
  material.aoMap = doorAmbientOcclusionTexture
  material.aoMapIntensity = 1
  material.displacementMap = doorHeightTexture
  material.displacementScale = 0.05
  material.metalnessMap = doorMetalnessTexture
  material.roughnesssMap = doorRoughnessTexture
  material.normalMap = doorNormalTexture
  material.normalScale.set(0.5, 0.5)
  material.transparent = true
  material.alphaMap = doorAlphaTexture*/

## Setup
Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```

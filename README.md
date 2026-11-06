# Avocado AR Exhibit

A mini museum exhibit built with A-Frame + AR.js. Point your phone at the **Hiro marker**.

## Features
- **Marker scene:** pedestal (cylinder), ball (sphere), cone, plaque (box), ring (torus), `<a-text>` title
- **Animation:** avocado rotates, ball bounces (position), ring spins
- **3D model:** Avocado GLB
- **Interaction:** tap the ball → colour change (`color-change`); tap the cone → avocado grows/shrinks and plaque toggles (`grow-toggle`, custom component)
- **Status banner:** red/green banner with text change on marker lost/found
- **Hosting:** https://didulangaweeraratne.github.io/ar-exhibit/

## Credits
- **Avocado** model by Microsoft, from the [Khronos glTF-Sample-Models](https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/Avocado) repo. Licence: **CC0 1.0** (public domain dedication).
- [A-Frame](https://aframe.io) 1.3.0 and [AR.js](https://github.com/AR-js-org/AR.js) 3.4.5 (MIT).

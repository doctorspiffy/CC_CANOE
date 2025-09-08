# CC_CANOE
Unity template for off-axis 3D stereoscopic rendering.
Supports interlaced, side-by-side, and top-bottom stereo.

Look at CCInstructions2025.pdf for details.

See below for an explanation of the versions of the software. I recommend using the latest version if possible. Avoid anything older than the CC2024 version.

Here is the download link for all the versions:
https://drive.google.com/drive/folders/1CvOhoQPEVKKqcLJVzQ67VyPYP87xCRBC?usp=sharing

**Versions:**
- CC2025-ALL-RP-2025-09-07.zip - Fixed a bug in the waypoint interpolation. Upgraded to Unity 6000.2. Using a scriptable game object to hold settings for stereo. Fixed build settings for URP and HDRP versions.
- CC2024-ALL-RP.zip - Contains a wholly new implementation that fixes the prior performance problem. This new version (tested on Unity 22.3.46f1) now supports Unity's Built-in Rendering Pipeline, Universal Rendering Pipeline, and the High Definition Rendering Pipeline. Read CCInstructions2024.pdf above for details. This version also adds Space Mouse support.

- URPCCElementalsEnhanced-2023-07-06.zip - Updated code to work with Unity's Universal Render Pipeline 2022 and RTHandle system. Tested with Unity LTS 2022.3.4f1. Do NOT use this version yet. Unity has a bug which makes the use of very large render textures too slow for practical use. This has NOT been fixed by Unity since November 2023. See: https://forum.unity.com/threads/terrible-render-texture-urp-performance-2022-2.1393462/
- URPCCElementalsEnhanced-2022-08-14.zip - Use this with version Unity 2021.3.4f1. Not compatible with Unity 2022. This version also includes code to use Unity's new input system so that Windows and Mac control of game controllers work properly. Recommend using Xbox wireless game controllers. For some reason the Mac will not work properly with the Logitech F310.
- URPCCElementalsEnhanced-2022-07-08.zip - Added two scripts to support using PC game controller for navigating around the space, and a script to record and traverse waypoints.
- URPCCElementals-2022-07-06.zip - Fixed a bug where window wasn't maximizing fully after resizing, leaving window title bar visible.
- URPCCElementals-2022-07-04.zip - Initial version.

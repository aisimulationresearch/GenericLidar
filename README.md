# GenericLidar
Source code for Unity implementation of lidar sensors

1. In the Unity, create empty game object and create a camera as a child of the empty object
2. Add GenericLidarRenderer.cs to empty game object and add GenericLidarSensor.cs to camera object.
3. For the GenericLidarSensor script in Unity editor, add depth.shader to "Depth Shader" and DepthScannerShader.compute to "Compute Shader Source"
4. Just in case, I have added lidar.unity file

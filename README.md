# Post-Process-Depth-Normals-Textures-Unity-3D
Post Process Depth Normals Textures:

we will create a  scene being rendered with the viewspace normals as colors, and then the depth value as colors
to get the values of depth and normals from DepthTextureMode.DepthNormals you need to use the function DecodeDepthNormal. This function is defined in the UnityCG.cginc include file, which, by the way, can be found on windows using this path: <program_files>/Unity/Editor/Data/CGIncludes/

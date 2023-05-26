## v1.2 (18.05.2023)

### Whats New:
- Add support for HDL-32e device model (model id 33) *No "DUAL return" support
- Added support HDRP VFX Graph *check "Velodyne Viewer HDRP.pdf" inside Documentation folder
- Added support HDRP Custom Pass Rendering *check "Velodyne Viewer HDRP.pdf" inside Documentation folder
- Added support for Mac Metal (experimental shaders added)
- Fixed: Mesh intensity shader was missing _Granularity property

### Known issues
- View/report issues on github : https://github.com/unitycoder/VelodyneLidarViewer/issues

------------------------------------------------------------------------------------------------------------------------------------------------

## v1.1.1 (24.03.2022)

### Whats New:
- Unity version upgrade to 2019.4.19f1
- Added example scene for feeding your own point data into viewer ("Example-Feed-Custom-Data")
- Added humanreadable count debug logs (for point count and file sizes: 1000000 > 1M)
- Added public methods info: https://github.com/unitycoder/VelodyneLidarViewer/wiki/API
- Added HDRP setup instructions: https://github.com/unitycoder/VelodyneLidarViewer/issues/5

------------------------------------------------------------------------------------------------------------------------------------------------

## v1.1 (24.06.2020)

## Added:
- DX11 Uber shader: RainbowMode now has Intensity mode (draws point original intensity color only)

------------------------------------------------------------------------------------------------------------------------------------------------

## Velodyne Lidar Viewer For Unity v1.0 (1.3.2020)

First version!

### Initial Features
- Supported devices: UltraPuck (VLP32C), Puck (VLP16)
- Large pcap file streaming (stream from disk, required for +2gb pcap files, but can be used with smaller files to instantly start playback)
- UDP live listener (receive data from live device connected using LAN cable)
- PCAP loader (load whole file for playback)
- Playback controls: Pause,Play,Rewind,Forward (not available for live stream, except pause)
- DX11, CommandBuffer and Mesh - rendering modes
- Special shaders with customizable options (Gradients, Rotation, Filter, Point size, View angle filter, Distance filter..)
- Using Unity 2018.4.8f1 (but works on later versions also)
- Supports VR (tested on Vive, Rift S, Cosmos, Quest*) *Quest only supports PCAP playback with mesh rendering.

### Limitations
- HDRP/URP renderpipelines are not supported!

------------------------------------------------------------------------------------------------------------------------------------------------

### Known issues
- View/report issues on github : https://github.com/unitycoder/VelodyneLidarViewer/issues

### Disclaimer:
VELODYNE is a trademark of Velodyne LiDAR, Inc. (not affiliated with this plugin)

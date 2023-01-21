# OpenCV with DNN build script for Jetson Xavier NX

This script builds OpenCV from source on Tegra (Nano, NX, AGX, etc.).

However, it has been only tested and verified for Jetson Xavier NX with JetPack 5.0.2. 

For other Tegra device and JetPack versions some twick need to be made. 

## Usage:
```shell
./build_opencv.sh
```

## Specifying an OpenCV version (git branch)
```shell
./build_opencv.sh 4.5.4
```

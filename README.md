# realsense_openni_drivers
Precompiled OpenNI2 Drivers for RealSense D400 Series Camera

Supported Platform：Ubuntu x64 & Jetson TX2
## Installation
Download the corresponding .so file for your platform.

    sudo cp librs2driver.so.0 /usr/lib/OpenNI2/Drivers/
    sudo ln -s /usr/lib/OpenNI2/Drivers/librs2driver.so.0 /usr/lib/OpenNI2/Drivers/librs2driver.so
## Test
    sudo apt-get install openni2-utils
    NiViewer2
